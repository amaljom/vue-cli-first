<template>
  <div class="displayDiv">
    <div class="background">
        <h1 class="text-white">BHO NTELESCOPIO</h1>
    </div>
    <div class="background2">
        <h1 class="text-white"> E UN UCCELLO CHE CAMMINA AL CONTRARIO</h1>
    </div>
  </div>
  
</template>

<script>

</script>

<style lang="scss">
  *{
    margin: 0 auto;
  }
  .displayDiv{
    display: flex;
  }
  .background{
    width: 700px;
    height: 470px;
    background-image: url(https://static01.nyt.com/images/2022/07/12/multimedia/12WEBB-HP5/12WEBB-HP5-tmagArticle.jpg);
    background-size: contain;
  }
  .background2{
    width: 700px;
    height: 470px;
    background-image: url(file:///D:/esercizi-boolean/vue-cli-first/src/assets/Cattura.PNG);
    background-size: cover;
  }
  .text-white{
    color: white;
  }
</style>