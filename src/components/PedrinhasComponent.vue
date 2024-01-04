<template>
    <div class="wrap">
      <div>
        <div class="pedrinha">
          <img class="pedrinhaImg" src="../assets/eucaristiaPedrinha.png" alt="Primeira Pedrinha: Eucaristia">
        </div>  
          <p class="pedrinhaTitulo">Eucaristia</p>
          <p class="pedrinhaDesc">Nos programamos para ir à Santa Missa e comungar do corpo de Cristo todos os dias.</p>
      </div>

      <div>
        <div class="pedrinha">
          <img src="../assets/palavraPedrinha.png" alt="Segunda Pedrinha: Palavra" class="pedrinhaImg">
        </div>  
          <p class="pedrinhaTitulo">Palavra</p>
          <p class="pedrinhaDesc">Separamos um tempo para investir "gastar", meditando a Palavra de Deus.</p>
      </div>

      <div>
        <div class="pedrinha">
          <img src="../assets/terçoPedrinha.png" alt="" class="pedrinhaImg">
        </div>          
          <p class="pedrinhaTitulo">Terço</p>
          <p class="pedrinhaDesc">Rezamos o terço todos os dias, contemplando a vida de Jesus através dos mistérios</p>
      </div>

      <div>
        <div class="pedrinha">
          <img src="../assets/jejumPedrinha.png" alt="" class="pedrinhaImg">
        </div>          
          <p class="pedrinhaTitulo">Jejum</p>
          <p class="pedrinhaDesc">Pela salvação das almas, vivemos o jejum que a Igreja nos propõe as sextas-feiras.</p>
      </div>

      <div>
        <div class="pedrinha">
          <img src="../assets/confissãoPedrinha.png" alt="" class="pedrinhaImg">
        </div>  
          <p class="pedrinhaTitulo">Confissão</p>
          <p class="pedrinhaDesc">Sempre que estivermos em pecado grave ou nossa consciência pedir, recorremos a este tão valioso sacramento.</p>
      </div>
    </div>
</template>

<script>
export default{
    name: 'PedrinhasComponent'
}

</script>

<style scoped>
  .wrap{
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    margin-top: 20px;
  }

  .pedrinha{
    display: flex;
    background-color: gray;
    width: 100px;
    height: 100px;
    margin-left: auto;
    margin-right: auto;
    border-radius: 50%;
  }

  .pedrinhaImg{
    display: flex;
    padding: auto;
  }

  .pedrinhaTitulo{
    color: black;
    text-align: center;
    text-decoration: underline;
    margin-top: 10px;
    margin-bottom: 10px;
  }

  .pedrinhaDesc{
    color: black;
    max-width: 150px;
    font-size: 15px;
    text-align: center;
    /* text-align: left; */
  }
</style>