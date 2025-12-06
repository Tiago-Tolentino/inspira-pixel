<script setup>
// imports
import facebook from "../assets/facebook.png"
import instagram from "../assets/instagram.png"
import linkedin from "../assets/linkedin.png"
import twitter from "../assets/twitter.png"
</script>

<template>
    <footer>
        <div class="container1">
            <div class="container_ul">
                <ul>
                    <h3>Contato</h3>
                    <div>
                    <li>contato@inspiralens.com</li>
                    <li>Central de ajuda</li>
                    <li>Rio de Janeiro - Brasil</li>
                    </div>
                </ul>
                <ul>
                    <h3>Sobre</h3>
                    <div>
                    <li>Politicas</li>
                    <li>Politicas de privacidade</li>
                    <li>Blog</li>
                    </div>
                </ul>
            </div>
            <div class="newsletter">
                <h3>Assine nossa newsletter</h3>
                <input type="text" placeholder="Digite seu e-mail">
                <button>Inscrever-se</button>
            </div>
        </div>
        <div class="redes_sociais">
            <img :src="facebook" alt="logo facebook">
            <img :src="instagram" alt="logo instragram">
            <img :src="linkedin" alt="logo linkedin">
            <img :src="twitter" alt="logo twitter">
        </div>
    </footer>
</template>

<style scoped lang="scss">
footer{
    margin: 2rem;
    display: flex;
    flex-direction: column;
    align-items: center;

    .container1{
        margin-bottom: 1rem;
        display: flex;
        width: 90vw;
        height: 20vh;
        justify-content: space-between;


        .container_ul{
            display: flex;
            justify-content: space-between;
            width: 35vw;
            ul{
                display: flex;
                flex-direction: column;
                gap: 1rem;
                list-style: none;
                div{
                    display: flex;
                    flex-direction: column;
                    height: 12vh;
                    justify-content: space-between;
                }
            }
        }
    }
    .newsletter{
        display: flex;
        flex-direction: column;
        width: 25vw;
        justify-content: space-between;

        h3{
            font-weight: 500;
            font-size: 24px;
        }

        input{
            padding: 10px;
            height: 3rem;
            width: 100%;
            border: none;
            border-radius: 3px;
            background-color: #6e6e6e3b;
            color: #E6E6E63B;
        }

        button{
            border: none;
            width: 7rem;
            height: 2rem;
            border-radius: 5px;
            color: white;
            background-color: #E1306C;
            cursor: pointer;
        }

    }

    .redes_sociais{
        width: 10vw;
        display: flex;
        justify-content: space-between;
        img{
            cursor: pointer;
        }
    }
}
</style>