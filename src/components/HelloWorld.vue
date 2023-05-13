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
  <div>
    <div class="div-2">
      <b class="images">1,20000</b>
    <b class="images">Jobs</b>
    <b class="images">For you</b>
    </div>
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
  background-size: contain;
  margin-top: 30px;
}

.images {
  padding: 20vh 10vw;
  flex-shrink: 6;
}

/* Media query for screens less than 600px wide */
/* @media screen and (max-width: 600px) {
  .div-2 {
    margin-top: 20px;
  }
} */

/* Media query for screens between 600px and 900px wide */
/* @media screen and (min-width: 600px) and (max-width: 900px) {
  .div-2 {
    margin-top: 40px;
  }
} */

/* Media query for screens greater than 900px wide */
/* @media screen and (min-width: 900px) {
  .div-2 {
    margin-top: 50px;
  }
} */
</style>
