<template>
  <div id="nav">
    <router-link to="/" id="logourl">
        <img :src="logo" id="logo" :alt="alt">
    </router-link>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">Sobre</router-link> |
    <router-link to="/Contato">Contato</router-link>
  </div>
</template>
<script>
export default {
    name: "Navbar",
    props: ["logo", "alt"]
}
</script>
<style scoped>
  #nav{
    background-color: #222;
    border-bottom: 5% solid #111;
    padding: 1% 4%;
    display: flex;
    justify-content: flex-end;
    align-items: center;

  }
#logourl{
  margin:auto;
margin-left: 0;
}
  #logo{
    width: 40px;
    height: 40px;
    filter:brightness(10)
  }
  #nav a{
    text-decoration: none;
    padding: 12px;
    transition: .5s;
    color: #fff
  }
  #nav a:hover {
    color: cyan;
  }
</style>