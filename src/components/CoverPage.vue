<template>
    <div class="bg-img">
        <div class="title">
            <h1>Redefiniendo la experiencia del cliente</h1>
            <h2>en las salas de espera</h2>
        </div>
    </div>
</template>
<script>
    export default {
        name: 'CoverPage'
    }
</script>
<style scoped>
    .bg-img{
        height: 26rem !important;
        background-image: url('../assets/bg_orange.jpg');
        background-repeat: no-repeat;
        align-items: center;
        display: flex;
        opacity: .7;
    }
    .title, .bg-img{
        width: 100%;
    }
    h1, h2 {
        color: aliceblue;
        font-weight: bold;
        text-align: center;
    }
    h1 {
        text-shadow: 2px 6px 4px black;
    }
    h2 {
        text-shadow: 2px 4px 1px black;
    }
</style>