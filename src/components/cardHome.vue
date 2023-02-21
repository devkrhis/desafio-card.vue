<template>
    <div id="backgroundCard">
        <h1> Esse é o componente pai </h1>
        <div class="card">
            <svg-icon type="mdi" :path="path" class="cardIcon"></svg-icon>
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

@import url('https://fonts.googleapis.com/css2?family=Signika+Negative:wght@300;500&display=swap');

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
    padding: 1% 0% 2% 1%;
    border-radius: 20px;
    width: 25vh;
    background-color: #ffffff;
    box-shadow: -7px 10px 25px #d5d7e3;
}

dadosCardHome {
    display: flex;
    flex-direction: column;
}

.cardTitulo {
    font-weight: bold;
    font-size: larger;
    font-family: 'Signika Negative', sans-serif;
    margin-bottom: 3%;
}

.cardSubtitulo {
    font-family: 'Signika Negative', sans-serif;
    font-size: x-small;
    width: 8vh;
    word-wrap: break-word;

}

</style>