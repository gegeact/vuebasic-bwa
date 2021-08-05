<template>
  <div class="logos-wrapper">
        <h2 class="title-header">Find Best Logo</h2>  
          <div class="item-logos">
            <img class="logo" alt="Vue logo" src="../assets/starbak.png">
          </div>
          <div class="item-logos">
            <img class="logo" alt="Vue logo" src="../assets/gugel.png">
          </div>
          <div class="item-logos">
            <img class="logo" alt="Vue logo" src="../assets/tut.png">
          </div>
          
  </div>
</template>

<script>
export default {
  name: 'Logos'
}
</script>

<style scoped>

.title-header {
  margin-bottom:80px ;
}

.logos-wrapper {
  width: 70%;
  margin: auto;
  overflow: hidden;
}

.item-logos {
  float: left;
  margin-right: 20px;
  margin-top: 20px;
  width: 150px;
  height: 150px;
}

.item-logos .logo {
  width: 150px;
  height: 150px;
}

</style>
