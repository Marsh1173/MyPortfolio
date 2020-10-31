<template>
  <div class="about">
    <h1>About Me</h1>
    <form action="https://www.google.com/maps/place/Quincy,+WA+98848/@47.2274422,-119.9238131,12z/data=!3m1!4b1!4m5!3m4!1s0x5499753251ef4209:0x8dbd9a4e2a88a08c!8m2!3d47.2342997!4d-119.8525504" target="_blank">
      <p>From <input type="submit" value="Quincy, WA" />,</p>
    </form>
    <form action="https://www.byu.edu/" target="_blank">
      <p>Currently enrolled in <input type="submit" value="BYU" />,</p>
    </form>
    <p>Graduating Summer Semester 2022,</p>
    <form action="/../Resume.pdf" target="_blank">
      <p>My <input type="submit" value="Resume" /></p>
    </form>
  </div>
</template>

<script>

export default {
  name: 'About',
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
