<template>
    <div id="show-main">
            
        <div id="photo1">
            
        </div>
        <div class="text-show">
            <h1>PINTADOS À TINTA</h1>
            <P>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin at facilisis sapien. Maecenas hendrerit blandit ipsum a mattis. Nunc rhoncus efficitur ipsum non cursus. Phasellus ac massa bibendum, mollis nisl a, vestibulum ligula. Nunc at arcu quis quam vestibulum aliquam.  Donec fringilla ligula lacus, rhoncus consequat libero iaculis et.</P>
            <br/><br/>
            <ButtonMost />
        </div>

    </div>
    <div ><br/><br/></div>
    <div id="show-main">
        <div class="text-show">
            <h1>PRETO E BRANCO</h1>
            <P>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin at facilisis sapien. Maecenas hendrerit blandit ipsum a mattis. Nunc rhoncus efficitur ipsum non cursus. Phasellus ac massa bibendum, mollis nisl a, vestibulum ligula. Nunc at arcu quis quam vestibulum aliquam.  Donec fringilla ligula lacus, rhoncus consequat libero iaculis et.</P>
            <br/><br/>
            <ButtonMost />
        </div>    
        <div id="photo2">
            
        </div>
        

    </div>
    
</template>
<script>
import ButtonMost from "../components/ButtonMost.vue"
export default {
    name: "Show",
    components: { ButtonMost }
}

</script>
<style scoped>
#show-main{
    display: flex;
    box-shadow: 0 30px 64px -25px rgb(0 0 0 / 24%);
    background-color: #222;
    width: 100%;
    height: 600px;
    margin-left: 1%;
    justify-content: center;
    align-content: center;
    flex-wrap: nowrap;
}
#photo1{

    background-image: url('/img/itachi.jpeg');
    height: 100%;
    width: 35%;
    background-size: cover;
    background-position: center;
    align-self: flex-start;
}
#photo2{

    background-image: url('/img/mascara.jpeg');
    height: 100%;
    width: 35%;
    background-size: cover;
    background-position: center;
    align-self: flex-start;
}
.text-show h1{
color: #fff;
padding-top: 60px;
text-align: center;
}
.text-show{
    width: 65%;
    color: white;
    font-size: 25px;
    padding:  5px 5% 5% 5%;
}
</style>