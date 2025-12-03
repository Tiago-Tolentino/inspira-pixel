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
    // border: solid;
    width: 35vw;
    // height: 60vh;
    img{
        width: 100%;
        height: 100%;
        border-radius: 10px;
    }
}
</style>