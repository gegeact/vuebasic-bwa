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
          </div><div class="item-logos">
            <img class="logo" alt="Vue logo" src="../assets/starbak.png">
          </div>
          <div class="item-logos">
            <img class="logo" alt="Vue logo" src="../assets/gugel.png">
          </div>
          <div class="item-logos">
            <img class="logo" alt="Vue logo" src="../assets/tut.png">
          </div><div class="item-logos">
            <img class="logo" alt="Vue logo" src="../assets/starbak.png">
          </div>
          <div class="item-logos">
            <img class="logo" alt="Vue logo" src="../assets/gugel.png">
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
  margin-bottom:50px ;
  text-align: center;
}

.logos-wrapper {
  width: 58%;
  margin: auto;
  overflow: hidden;
}

.item-logos {
  float: left;
  margin: 70px 35px 0px 35px;
  /* margin-right: 70px; */
  /* margin-top: 70px; */
  width: 150px;
  height: 150px;
}

.item-logos .logo {
  width: 150px;
  height: 150px;
}

</style>
