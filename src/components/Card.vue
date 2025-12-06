<script setup>
defineProps(["imagem"])
</script>

<template>
    <div class="card">
        <img :src="imagem" alt="imagens">
    </div>

</template>

<style scoped lang="scss">
.card{
    width: 15vw;
    height: 45vh;
    img{
        width: 100%;
        height: 100%;
        border-radius: 10px;
        object-fit: cover;
    }
}
</style>