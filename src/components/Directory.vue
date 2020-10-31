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

    <li class="nav-item dropdown">
      <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
        CS224
      </a>
      <div class="dropdown-menu" aria-labelledby="navbarDropdown">
        <a class="dropdown-item disabled" href="#">Coming soon</a>
      </div>
    </li>
    <li class="nav-item dropdown">
      <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
        CS235
      </a>
      <div class="dropdown-menu" aria-labelledby="navbarDropdown">
        <a class="dropdown-item disabled" href="#">Lab 1 Replit</a>
        <a class="dropdown-item disabled" href="#">Lab 2 Replit</a>
        <a class="dropdown-item disabled" href="#">Lab 3 Replit</a>
        <a class="dropdown-item disabled" href="#">Lab 4 Replit</a>
        <a class="dropdown-item disabled" href="#">Lab 5 Replit</a>
        <a class="dropdown-item disabled" href="#">Lab 6 Replit</a>
      </div>
    </li>
    <li class="nav-item dropdown">
      <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
        CS260
      </a>
      <div class="dropdown-menu" aria-labelledby="navbarDropdown">
        <a class="dropdown-item" href="http://lab1.natehroylance.com/">Lab 1</a>
        <a class="dropdown-item" href="http://lab2.natehroylance.com/">Lab 2</a>
        <a class="dropdown-item" href="http://lab3a.natehroylance.com/">Lab 3a</a>
        <a class="dropdown-item" href="http://motherearth.natehroylance.com/">Lab 3b</a>
        <div class="dropdown-divider"></div>
        <a class="dropdown-item" href="http://cp1.natehroylance.com/">Creative Project 1</a>
        <a class="dropdown-item" href="http://cp2.natehroylance.com/">Creative Project 2</a>
      </div>
    </li>

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
</style>
