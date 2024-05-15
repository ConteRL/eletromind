<template>
  <div id="home-start" class="container-fluid d-flex  align-items-center">

    <div class="row align-items-center h-75">
      <div id="welcome-text" class="col-6 px-5">
        <div class="text-start text-light">
          <h1 id="welcome-phrase">Welcome!!</h1>
          <h2>Come and learn more about electronics and computing.</h2>
        </div>
      </div>

      <div class="col-6 px-5">
        <img src="../assets/circuits/parallel-leds.png" id="welcome-img" class="rounded-4 border border-3 p-2" alt="LEDs in parallel">
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'Welcome',
    components: {

    }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Fugaz+One&display=swap');

#home-start {
  width: 100vw;
  height: 75vh;
  position: relative;
  background-color: #2B3A41;
  background-image: url("./../assets/home_circuit_bg.png");
  background-repeat: no-repeat;
  background-position: right center;
  background-size: cover;
}

#welcome-text {
  text-shadow: 1px 2px 2px #00A2E2, 0 0 0.1em white, 0 0 0.1em white;
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