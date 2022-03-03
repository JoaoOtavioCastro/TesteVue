<template>

    <div class="main-container" id="main"> 
        <h1>ONDE ME ENCONTRAR?</h1>

        <div id="sociais">
            <Whatsapp />
            <Instagram />
            <Twitter />
            <Telegram />
        </div>
        </div>
</template>
<style scoped>
#main{
      margin-left: -5%;
      margin-right: -5%;
}
#main-cont{
    background-color: #222;
    display: flex;
    align-items: center;
}
#sociais{
    display: flex;
}
</style>
<script>

import Whatsapp from "../components/Whatsapp.vue";
import Instagram from "../components/Instagram.vue";
import Twitter from "../components/Twitter.vue";
import Telegram from "../components/Telegram.vue";
export default {
    name: "Contato",
  components: {
    Whatsapp,
    Instagram,
    Twitter,
    Telegram
}
}
</script>
