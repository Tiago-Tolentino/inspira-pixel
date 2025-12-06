<script setup>
// imports
import Card from './Card.vue';
import axios from 'axios';
import { ref } from 'vue';

const imagens = ref([])

// funcao assincrona ->

async function carregarImagens(){
    const res = await axios.get("https://picsum.photos/v2/list?page=3&limit=30");

    imagens.value = res.data;
    console.log(res)
}

carregarImagens();
</script>

<template>
    <h2>Inpire-se</h2>
    <section class="inspire">
    <Card
    v-for="img in imagens"
    :imagem="img.download_url"
    />
    
    </section>
</template>

<style scoped lang="scss">
.inspire, h2{
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 10px;
    margin: 2rem;
}

</style>