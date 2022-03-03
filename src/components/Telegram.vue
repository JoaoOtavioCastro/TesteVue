<template>
    <div class="link-social">

        <div id="tel" ></div><br/><br/>
        <h3>Instagram</h3><br/>
        <p>Me encontre no telegram</p> 
        <a href="#" target="blank">@jotavioo</a>


    </div>
</template>
<style scoped>
#tel{
    background-image: url('/img/icon_telegram.png');
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
    name: "Telegram"
}
</script>