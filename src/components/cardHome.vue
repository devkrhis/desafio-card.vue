<template>
    <div id="backgroundCard">
        <h1> Esse é o componente pai </h1>
        <div class="card">
            <svg-icon type="mdi" :path="path"></svg-icon>
            <dadosCardHome class="cardTitulo" :CardTitulo="cardData[0].titulo"/>
            <dadosCardHome class="cardSubtitulo" :CardSubtitulo="cardData[0].subtitulo"/>
        </div>

    </div>
    
</template>

<script>
import dadosCardHome from './dadosCardHome.vue';
import SvgIcon from '@jamescoyle/vue-icon';
import { mdiWalletOutline } from '@mdi/js';
export default {
    components: {
        dadosCardHome,
        SvgIcon
    },
    data(){
        return {
            path: mdiWalletOutline,
            cardData: [
                {
                    titulo: "$143,624",
                    subtitulo: "Your Bank Balance"

                }
            ],
            
        }
    }
    
    
}
</script>

<style scoped>

#backgroundCard {
    width: auto;
    height: auto;
    background-color: #f9fafc;
    padding-bottom: 20vh;
}

.card {
    border: 0px solid black;
    margin-bottom: 1%;
    margin-left: 1%;
    padding: 3% 0% 3% 0%;
    border-radius: 20px;
    width: 25vh;
    background-color: #ffffff;
    box-shadow: -7px 10px 25px #d5d7e3;
}

dadosCardHome {
    display: flex;
    flex-direction: column;
}

</style>