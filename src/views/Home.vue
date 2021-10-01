<template>
  <div class="home">
  <h1>Hello there!</h1>
  <ul>
    <li>
      <h1>Check out my CS260 projects!</h1>
    </li>
    <li>
    <form action="https://github.com/Marsh1173" target="_blank">
      <h1>Github Projects - <input type="submit" value="github.com/Marsh1173" /></h1>
    </form>
    </li>
    <li>
    <form>
      <h1>Hackerrank - Coming soon!</h1>
    </form>
    </li>
    <li>
          <p>This website has built during my whole <br> education. For the best example of my <br> programming ability, check out <br> Block Game and InterByte Heroes <br> in the CS 260 tab.</p>

    </li>
  </ul>
  </div>
</template>

<script>
export default {
  name: 'Home',
  components: {

  }
}
</script>

<style scoped>
h1 {
  margin-top: 30px;
  font-size: 2rem;
}
p {
  margin-top: 30px;
  font-size: 1.3rem;
}
input {
  border: none;
  border-radius: 10px;
  padding: 0px 10px;
  background-color: white;
  color: #438f69;
  box-shadow: 0 0px 1px 0 rgba(0,0,0,0.24), 0 0px 3px 0 rgba(0,0,0,0.19);
}
input:hover {
  color: #438f69;
  box-shadow: 0 0px 1px 0 rgba(0,0,0,0.24), 0 0px 10px 0 rgba(0,0,0,0.19);
}
input:active {
  box-shadow: 0 0px 1px 0 rgba(0,0,0,0.24), 0 0px 3px 0 rgba(0,0,0,0.19);
}
input:focus {
  outline:0;
}
</style>
