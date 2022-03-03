<template>
  <Navbar :logo="logo_src" :alt="app_name"/>
  <router-view/>
  <Footer />
</template>

<script>
  import Navbar from './components/Navbar.vue';
  import Footer from './components/Footer.vue';


  export default {
    components: {
      Navbar,
      Footer
    },
    data() {
      return {
        logo_src: "/img/pincel.png",
        app_name: "Página do João"
      }
    }
  }

</script>
<style>
*{
  font-family: Helvetica;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
.main-container{
  margin: 5%;
  min-height:250px;
  text-align: justify;
}
.main-container h2{
  text-align: center;
}
h1{
  text-align: center;
  font-size: 42px;
  margin-bottom: 30px;

}
.link-social{
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  justify-items: center;
  flex-wrap: wrap;
  width: 34%;
  background-color: #222;
  color: #fff;
  padding: 5%;


}
</style>
