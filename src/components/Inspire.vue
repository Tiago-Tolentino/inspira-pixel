<script setup>
import Card from './Card.vue';
</script>

<template>
    <h2>Inpire-se</h2>
    <section class="inspire">
    <Card imagem="https://upload.wikimedia.org/wikipedia/commons/6/60/Mount_Fuji_from_Lake_Shoji_%2815443819010%29.jpg"/>
    <Card imagem="https://static.vecteezy.com/ti/fotos-gratis/p2/7304605-fuji-san-montanha-reflexao-no-lago-kawaguchiko-ao-nascer-do-sol-foto.jpg"/>
    <Card imagem="https://p2.trrsf.com/image/fget/cf/940/0/images.terra.com/2022/05/26/874995092-flor-de-cerejeira-para-jardim-foto-kapali-hesap.jpg"/>
    </section>
</template>

<style scoped lang="scss">
.inspire, h2{
    display: flex;
    justify-content: space-between;
    gap: 10px;
    margin: 2rem;
}

</style>