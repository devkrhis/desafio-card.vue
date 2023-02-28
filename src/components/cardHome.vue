<template>
  <div>
    <h2> My Card List </h2>
    <div id="backgroundCard">
      <div class="card" v-for="savingAllCards in cardData" :key="savingAllCards.key">
        <svg-icon type="mdi" :path="savingAllCards.path" class="cardIcon"></svg-icon>
        <dadosCardHome class="cardTitulo" :CardTitulo="savingAllCards.titulo"/>
        <dadosCardHome class="cardSubtitulo" :CardSubtitulo="savingAllCards.subtitulo"/>
      </div>
    </div>
  </div>
</template>

<script>
import dadosCardHome from "./dadosCardHome.vue";
import SvgIcon from "@jamescoyle/vue-icon";
import { mdiWalletOutline } from "@mdi/js";
import { mdiCalendarToday } from "@mdi/js";
export default {
  components: {
    dadosCardHome,
    SvgIcon,
  },
  data() {
    return {
    //   path: [mdiWalletOutline, mdiCalendarToday],
      cardData: [
        {
          path: mdiWalletOutline,
          titulo: "$143,624",
          subtitulo: "Your Bank Balance",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "22",
          subtitulo: "Teste 20",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7",
          subtitulo: "Employees working today",
        },
        {
          path: mdiCalendarToday,
          titulo: "7viagem",
          subtitulo: "Employees working today",
        },
      ],
    };
  },
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Signika+Negative:wght@300;500&display=swap");

div h2{
    align-items: center;
}

#backgroundCard {
  max-width: 1920px;
  min-width: 320px;
  max-height: 1080px;
  min-height: 568px;
  background-color: #f9fafc;
  padding-bottom: 20vh;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  margin-top: 1%;
}

.card {
  border: 0px solid black;
  margin-bottom: 1%;
  margin-left: 1%;
  padding: 1% 0% 2% 1%;
  border-radius: 20px;
  min-width: 150px;
  min-height: 150px;
  background-color: #ffffff;
  box-shadow: -7px 10px 25px #77777786;
}

.card dadosCardHome {
  display: flex;
  flex-direction: column;
}

.cardTitulo {
  font-weight: bold;
  font-size: larger;
  font-family: "Signika Negative", sans-serif;
  margin-bottom: 3%;
}

.cardSubtitulo {
  font-family: "Signika Negative", sans-serif;
  font-size: x-small;
  max-width: 50px;
  word-wrap: break-word;
}
</style>