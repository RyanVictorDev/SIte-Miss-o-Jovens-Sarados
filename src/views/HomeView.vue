<template>
  <div class="home">
    <img class="banner" alt="Padre Edi" src="../assets/padreEd.png">

    <p class="frase">A loucura de Deus é muito mais bonita que a sabedoria do homem.</p>

    <p class="pedrinhasFrase">Conheça as Cinco Pedrinhas</p>

    <PedrinhasComponent />
  </div>
</template>

<script>
import PedrinhasComponent from '@/components/PedrinhasComponent.vue';

export default {
  name: 'HomeView',

  components: {
    PedrinhasComponent
  }
}
</script>

<style scoped>
  .banner{
    width: 100%;
  }

  .frase{
    color: black;
    font-size: 20px;
    margin-top: 20px;
    margin-bottom: 35px;
    padding-top: 15px;
    padding-bottom: 15px;
    background-color: #D9D9D9;
    box-shadow: 3px 3px 6px 1px rgba(0, 0, 0, 0.57);
    text-shadow: 3px 3px 5px rgba(0, 0, 0, 0.5);
  }

  .pedrinhasFrase{
    color: black;
    font-size: 20px;
    text-shadow: 3px 3px 5px rgba(0, 0, 0, 0.5);
  }
</style>
