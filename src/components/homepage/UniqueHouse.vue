<template>
    <div class="banner">
        <img class="banner-image" src="../../assets/Banner_One.png" alt="image">
        <div class="banner-text">
            <h1 class="title">Пусть ваш дом будет уникальным</h1>
            <p class="title-text">Существует много вариаций Lorem Ipsum, которые можно использовать</p>
            <button class="button">Начать <span><img src="../../assets/Vector.png" alt="img"></span></button>
        </div>
    </div>
</template>
.
<script>

export default {
  name: 'UniqueHouse',
}
</script>

<style scoped>
    .banner {
        width: 930px;
        height: 550px;
        margin-top: 20px;
        padding: 20px 120px 0px 180px;
    }

    .banner-image {
        width: 1180px;
        height: 758px;
    }

    .banner-text {
        position: absolute;
        top: 300px;
        right: 724px;
    }

    .title {
        font-size: 55px;
        width: 520px;
    }

    .title-text {
        font-size: 22px;
        line-height: 40px;
        width: 520px;
    }

    .title, .title-text, .button {
        font-family: 'DM Serif Display', Helvetica, sans-serif;

    } 

    .button {
        font-size: 18px;
        background-color: #292f36;
        border-radius: 18px;
        color: #fff;
        padding: 20px;
    }
</style>
