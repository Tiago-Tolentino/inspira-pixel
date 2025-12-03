<script setup>
import { Icon } from "@iconify/vue";
import logo from "../assets/logo.png"
import search from "../assets/button-search.png"
import user from "../assets/button-user.png"
</script>

<template>
<header>
    <img :src="logo" alt="logo">
    <ul>
        <li>
            <img :src="search" alt="icone de pesquisa">
        </li>
        <li>
            <a href="">Inicio</a>
        </li>
        <li>
            <a href="">Galeria</a>
        </li>
        <li>
            <a href="">Favoritos</a>
        </li>
        <li>
            <img :src="user" alt="icone de usuario">
        </li>
    </ul>
</header>
</template>

<style scoped lang="scss">
header{
    //border: solid;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    margin: 2rem;

    ul{
        display: flex;
        gap: 1.5rem;
       // border: solid;
        flex-wrap: wrap;
        list-style: none;
        align-items: center;
    }

    a{
        text-decoration: none;
        color: black;
    }
}

</style>

