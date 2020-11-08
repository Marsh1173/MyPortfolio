<template>
<div id='header'>
  <header>
    <img src="/../starimg.jpg" />
  </header>
</div>
</template>

<script>
export default {
  name: 'HeaderImage',
}
</script>


<style scoped>
header {
  overflow: hidden;
}
header img {
  height: 200px;
  margin: none;
  padding: none;
  margin-left: 50%;
  transform: translateX(-50%);
  vertical-align: bottom;
  border-bottom: 2px solid gray;
}
@media only screen and (max-width: 779px) and (min-width: 669px) {
  header img {
    height: 150px;
  }
}
@media only screen and (max-width: 668px) {
  header img {
    height: 100px;
  }
}
</style>
