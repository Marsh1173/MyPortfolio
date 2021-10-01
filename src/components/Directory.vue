<template>
<nav class="navbar navbar-expand-md navbar-light bg-white">
<a class="navbar-brand"><img src="/../Ricon100.png"/></a>
<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
  <span class="navbar-toggler-icon"></span>
</button>

<div class="collapse navbar-collapse" id="navbarSupportedContent">
  <ul class="navbar-nav mr-auto">

    <li class="nav-item"><router-link class="nav-link btn btn-outline-success" to="/"><b>Home</b></router-link></li>
    <li class="nav-item"><router-link class="nav-link btn btn-sm btn-outline-secondary" to="/about"><b>About</b></router-link></li>
    <li class="nav-item"><router-link class="nav-link btn btn-sm btn-outline-secondary" to="/contact"><b>Contact</b></router-link></li>
    <li class="nav-item"><router-link class="nav-link btn btn-sm btn-outline-secondary" to="/cs260"><b>CS260</b></router-link></li>

  </ul>
</div>
</nav>
</template>

<script>
export default {
  name: 'Directory',
  methods: {
  }
}
</script>


<style scoped>
img {
  width: 50px;
  height: 45px;
}
.navbar {
  border-bottom: 3px solid gray;
}
.nav-item {
  margin-left: 20px;
}
.nav-link {
  width: 80px;
  height: 40px;
}
@media only screen and (max-width: 779px) {
img {
  width: 30px;
  height: 30px;
}
}
</style>
