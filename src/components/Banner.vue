<template>
    <div id="main-banner">
        <h1>UM DESENHISTA INICIANTE</h1>
    </div>
</template>

<script>
export default {
    name: "Banner"
}
</script>

<style scoped>
#main-banner{
    background-image: url('/img/Banner.jpg');
    background-position: 0 -250;
    background-size: cover;
    height: 400px;
    display: flex;
    align-items: center;
}
#main-banner h1{
    color: #fff;
    text-align: center;
    font-size: 60px;
    background-color: #222;
    padding: 20px 40px;
}
</style>