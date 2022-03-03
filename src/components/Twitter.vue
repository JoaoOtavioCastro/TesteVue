<template>
    <div class="link-social">

        <div id="tt" ></div><br/><br/>
        <h3>Twitter</h3><br/>
        <p>Me siga no Twitter</p> 
        <a href="#" target="blank">@jotaviozera</a>


    </div>
</template>
<style scoped>
#tt{
    background-image: url('/img/icon_twitter.png');
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
    name: "Twitter"
}
</script>