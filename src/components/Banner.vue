<script setup>
import fotografo from "../assets/fotografo.png"
</script>

<template>
    
    <section class="banner">
        <div>
        <h1>Onde a paisagem vira 
        <span>inspiração</span>.</h1>
        <p>Explore paisagens, cores e luzes que inspiram novas histórias através da fotografia.</p>
        </div>
        <img :src="fotografo" alt="fotografo banner">
    </section>

</template>

<style scoped lang="scss">
    .banner{
        display: flex;
        justify-content: space-around;
        margin: 2rem;
        span{
            color: #E1306C;
            font-size: 4.5rem;
        }
    }

    div{
        width: 60vw;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }

</style>