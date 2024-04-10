<script>
    export default {
        name: 'AppHero'
    }

</script>

<template>
    
    <div class="hero">
        <h2>Jumbotron Taylor</h2>
    </div>

</template>

<style>
    .hero {
        margin: 0 auto;
        width: 1200px;
        height: 600px;
        display: flex;
        align-items: center;
        justify-content: center;
        background-image: url('../assets/img/taylor-jumbotron.jpeg');
        background-size: cover;
        position: relative;
    }

    .hero:before {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-color: #000;
        opacity: 0.5;
    }

    h2 {
        font-family: Arial, Helvetica, sans-serif;
        color: #fff;
        z-index: 10;
    }
</style>