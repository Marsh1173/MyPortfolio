<template>
  <div id="cs260">
    <h1>My Web Development Projects</h1>
    <div id='projects'>
    <div v-for="project in this.projects" :key="project.id">
      <a v-bind:href="project.url">
      {{project.name}}
      <img v-bind:src="project.image" v-bind:alt="project.alt"/>
      <p>{{project.date}}</p>
      </a>
    </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CS260',
  computed: {
    projects() {
      return this.$root.$data.projects;
    }
  }
}
</script>

<style scoped>
#cs260 {
  display: flex;
  flex-direction: column;
  width: 100%;
}
#projects {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  align-self: center;
  width: 80%;
  justify-content: space-around;
}
a {
  display: flex;
  flex-direction: column;
  margin: 20px;
  width: 227px;
  border: 1px solid darkgrey;
  border-radius: 10px;
  background-color: white;
  color: #438f69;
  box-shadow: 0 0px 1px 0 rgba(0,0,0,0.24), 0 0px 3px 0 rgba(0,0,0,0.19);
  font-size: 2rem;
}
a p {
  font-size: 1.2rem;
  color: #2f3340;
  margin: 5px;
}
a img {
  margin: 0px;
  width: 225px;
  height: 200px;
  border: 1px solid darkgrey;
  border-radius: 7px;
  font-size: 1rem;
}
a:hover {
  box-shadow: 0 0px 1px 0 rgba(0,0,0,0.24), 0 0px 20px 0 rgba(0,0,0,0.25);
  text-decoration: none;
}
a:active {
  box-shadow: 0 0px 1px 0 rgba(0,0,0,0.24), 0 0px 3px 0 rgba(0,0,0,0.2);
}
a:focus {
  outline:0;
}

@media only screen and (max-width: 1000px) and (min-width: 780px) {
  a {
    width: 272px;
  }
  a img {
    width: 270px;
    height: 250px;
  }
}
@media only screen and (max-width: 779px) and (min-width: 669px) {
  h1 {
    font-size: 1.5rem;
  }
}
@media only screen and (max-width: 668px) {
  h1 {
    font-size: 1.2rem;
  }
  a {
    width: 152px;
  }
  a img {
    width: 150px;
    height: 140px;
  }
}
</style>
