<template>
    <div style="text-align: center;">
                <button type="submit" id="btn" ><a id="link" href="https://www.instagram.com/otaviodrawings/" target="_blank">Veja mais</a></button>
            </div>
</template>
<style scoped>
#btn{
    background: linear-gradient(135deg,#433 0%,#233 100%);
    color: #fff;
    font-size: 25px;
    padding: 10px 20px;
    border-radius: 50px;
    text-align: center;
    transition-property: all;
	transition-duration: .5s;
	transition-timing-function: cubic-bezier(0, 1, 0.5, 1);
}
#link{
    color: #fff;
    font-size: 25px;
    text-decoration: none;
}

</style>
<script>
export default {
    name: "ButtonMost"
}
</script>