<template>
<banner />
  <div class="main-container">    
    <show />
  </div>
</template>

<script>
import Banner from "../components/Banner.vue"
import Show from "../components/Show.vue"

export default{
  name: "Home",
  components: {
    Banner,
    Show
  }
}
</script>
