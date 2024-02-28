<script>
export default {
    name: 'AppHero',
}
</script>

<template>
    <div class="jumbo-container">
        <img class="img-jumbo" src="../assets/img/scala.jpg" alt="">
    </div>
</template>

<style>
.jumbo-container {

    width: 80%;
    margin: 100px auto;
    height: 700px;
    text-align: center;
    overflow: hidden;
    max-width: 1300px;
    border: 20px solid white;
    margin-bottom: 50px;
}

.img-jumbo {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
</style>