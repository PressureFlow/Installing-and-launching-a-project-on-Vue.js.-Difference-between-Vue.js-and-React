<template>

    <div class="picture">
        <img src="../public/alex-suprun-A53o1drQS2k-unsplash.jpg" alt="#">
        <img src="../public/alexandr-podvalny-uaP8Efaz_Rk-unsplash.jpg" alt="#">
        <img src="../public/evgeny-tchebotarev-aiwuLjLPFnU-unsplash.jpg" alt="#">
    </div>

</template>


<script>

    export default {
        name: 'PictureVue',

    }

</script>

<style>
    .picture {
        display: flex; 
        width: 20%;
    }
    .picture img {
        width: auto;
        height: 200px;
        padding: 20px;       
    }

</style>