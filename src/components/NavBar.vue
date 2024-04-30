<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary" data-bs-theme="dark" id="navbar">
    <div class="container-fluid">
      <a class="navbar-brand" href="#"><span style="color: #00A7EA">Eletro</span>mind</a>

      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown"
        aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse position-absolute top-50 start-50 translate-middle" id="navbarNavDropdown">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Computing</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Electronics</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Articles</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
        </ul>
      </div>

      <div>
        <img style="height: 50px;" src="../assets/github.svg" alt="Logo do GitHub">
        <span class="text-light">/ConteRL</span>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'NavBar',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Fugaz+One&display=swap');

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: white;
  font-weight: 200;
}

a.active {
  text-decoration: underline 2px;
  text-underline-offset: 0.4rem;
}

#navbar {
  font-family: 'Fugaz One';
  height: 10%;
}
</style>
