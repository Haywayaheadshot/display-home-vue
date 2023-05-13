<template>
  <div class="div-1">
    <button class="buttons">
      button 1
    </button>
    <button class="buttons">
      button 2
    </button>
    <button class="buttons">
      button 3
    </button>
  </div>
  <div class="div-2">
    <b class="images">1,20000</b>
    <b class="images">Jobs</b>
    <b class="images">For you</b>
  </div>
</template>

<style scoped>
.div-1 {
  display: flex;
  flex-direction: column;
  gap: 10px;
  margin-bottom: 30px;
}

.buttons {
  background-color: green;
}

.div-2 {
  display: flex;
  flex-direction: row;
  gap: 20px;
  background-image: url(../assets/vue.svg);
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.images {
  padding: 20vh 10vw;
}
</style>
