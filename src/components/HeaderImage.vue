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
</style>
