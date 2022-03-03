<template>
    <div class="link-social">

        <div id="insta" ></div><br/><br/>
        <h3>Instagram</h3><br/>
        <p>Me siga no instagram</p> 
        <a href="https://www.instagram.com/otaviodrawings/" target="blank">@otaviodrawings</a>


    </div>
</template>
<style scoped>
#insta{
    background-image: url('/img/icon_insta.png');
    filter: contrast(0%);
    width: 100px;
    height: 100px;
    background-size: cover;
}
a{
    text-decoration: none;
    color: #fff;   
}
a:hover{
    color: #6ff
}
</style>
<script>
export default {
    name: "Instagram"
}
</script>