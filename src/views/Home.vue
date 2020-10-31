<template>
  <div class="home">
  <h1>Hello there!</h1>
  <br>
  <ul>
    <li>
      <p>Check out my CS260 projects!</p>
    </li>
    <li>
    <form action="https://github.com/Marsh1173" target="_blank">
      <p>Github Projects - <input type="submit" value="github.com/Marsh1173" /></p>
    </form>
    </li>
    <li>
    <form>
      <p>Hackerrank - Coming soon!</p>
    </form>
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
p {
  margin-top: 30px;
  font-size: 1.8rem;
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
