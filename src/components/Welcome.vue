<template>
  <div id="home-start" class="container-fluid">

    <div class="row align-items-center h-75">
      <div class="col-5 mx-0 px-0">
        <div class="text-start text-light">
          <h1 id="welcome-phrase">Welcome!!</h1>
          <h2>Come and learn more about electronics and computing.</h2>
        </div>
      </div>

      <div class="col-5 mx-0 px-4 ali">
        <img src="../assets/circuits/parallel-leds.png" id="welcome-img" class="rounded-4 border border-3 p-2" alt="LEDs in parallel">
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'Welcome'
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Fugaz+One&display=swap');

#home-start {
  width: 100vw;
  height: 80vh;
  position: relative;
  background-color: #2B3A41;
}

.col-4 {
  background: blue;
}

#welcome-img {
  width: 100%;
  height: 100%;

  border-color: #00A2E2 !important;
}

#welcome-phrase {
  font-family: 'Fugaz One';
  color: white;

}
</style>