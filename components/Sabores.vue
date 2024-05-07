<template>
  <div>
    <div id="container">
      <div class="pl-3">
      <div id="caixa">
        <img  src="https://tse3.mm.bing.net/th?id=OIP.RPpmGYO9KGsameOAI2PARgHaHa&pid=Api&P=0&h=180" alt="">
      </div>
      </div>
      <div class="pl-3">
      <div id="caixa">
        <img src="https://tse3.mm.bing.net/th?id=OIP.AsVS8cYSdrVFLo0AEFhZvAAAAA&pid=Api&P=0&h=180" alt="">
      </div>
      </div>
      <div class="pl-3">
      <div id="caixa">
        <img src="https://tse2.mm.bing.net/th?id=OIP.uQXq50-ShncuASgHdqzkQwAAAA&pid=Api&P=0&h=180" alt="">
      </div>
      </div>
    </div>
    <!--Sabores-->
    <div class="text-center text-purple-800 text-xl pb-2">Sabores</div>
    <div id="cont">
      <div id="borda">
        <div class="block_1">
          <div id="card">
            <div class="text-4xl pt-3 pb-2">🍌</div>
            <UButton color="purple" >Add</UButton>
          </div>
          <div id="card">
            <div class="text-4xl pt-3 pb-2">🍫</div>
            <UButton color="purple">Add</UButton>
          </div>
          <div id="card">
            <div class="text-4xl pt-3 pb-2">🍓</div>
            <UButton color="purple" >Add</UButton>
          </div>
        </div>
        <div class="block_2">
          <div id="card">
            <div class="text-4xl pt-3 pb-2">🍪</div>
            <UButton color="purple" >Add</UButton>
          </div>
          <div id="card">
            <div class="text-4xl pt-3 pb-2">☕</div>
            <UButton color="purple">Add</UButton>
          </div>
          <div id="card">
            <div class="text-4xl pt-3 pb-2">🥭</div>
            <UButton color="purple" >Add</UButton>
          </div>
        </div>
        <div class="block_3">
          <div id="card">
            <div class="text-4xl pt-3 pb-2">🥥</div>
            <UButton color="purple">Add</UButton>
          </div>
          <div id="card">
            <div class="text-4xl pt-3 pb-2">🍒</div>
            <UButton color="purple">Add</UButton>
          </div>
          <div id="card">
            <div class="text-4xl pt-3 pb-2">🍍</div>
            <UButton color="purple">Add</UButton>
          </div>
        </div>
      </div>
    </div>
    <!--finalizar-->
    <div class="flex items-center justify-center pt-8 pb-8">
     <UButton class="w-80" color="purple" block>Finalizar Pedido</UButton>
    </div>
  </div>
</template>

<script>

</script>


<style scoped>
  #container{
    display: flex;
    justify-content: center;
    align-items: center;
    margin-bottom: 19px;
  }
  #caixa{
    border-bottom: 2px solid purple;
    cursor: pointer;
  }
  @media (max-width: 1000px){
    #container{
      display: flex;
      flex-direction: column;
    }
    #caixa{
      margin-bottom: 10px;
    }
  }
  #cont{
    justify-content: center;
    align-items: center;
    display: flex;
  }
  #borda{
    width: 450px;
    height: auto;
  }
  .block_1, .block_2, .block_3{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 14px;
  }
  #card{
    width: 100px;
    height: 100px;
    background: #aaa;
    text-align: center;
  }
</style>