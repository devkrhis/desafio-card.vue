<template>
    <div>
        <div id="backgroundCard">
            <div class="card">
                <svg-icon type="mdi" :path="path1" class="cardIcon"></svg-icon>
                <dadosCardHome class="cardTitulo" :CardTitulo="cardData[0].titulo"/>
                <dadosCardHome class="cardSubtitulo" :CardSubtitulo="cardData[0].subtitulo"/>
            </div>
            <div class="card">
                <IconCalendar type="mdi" :path="path2" class="cardIcon"></IconCalendar>
                <dadosCardHome class="cardTitulo" :CardTitulo="cardData[1].titulo"/>
                <dadosCardHome class="cardSubtitulo" :CardSubtitulo="cardData[1].subtitulo"/>
            </div>

        </div>
    </div>    
</template>

<script>
import dadosCardHome from './dadosCardHome.vue';
import SvgIcon from '@jamescoyle/vue-icon';
import IconCalendar from '@jamescoyle/vue-icon';
import { mdiWalletOutline } from '@mdi/js';
import { mdiCalendarToday } from '@mdi/js';
export default {
    components: {
        dadosCardHome,
        SvgIcon,
        IconCalendar
    },
    data(){
        return {
            path1: mdiWalletOutline,
            path2: mdiCalendarToday,
            
            cardData: [
                {
                    titulo: "$143,624",
                    subtitulo: "Your Bank Balance"

                },
                {
                    titulo: "7",
                    subtitulo: "Employees working today"

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
    display: flex;
    flex-direction: row;
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

.card dadosCardHome {
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
    width: 10vh;
    word-wrap: break-word;

}

</style>