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
        justify-content: space-between;
        margin: 2rem;
        span{
            color: red;
            font-size: 4.5rem;
        }
    }

    div{
        border: solid;
        width: 70vw;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }

</style>