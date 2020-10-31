<template>
  <div class="contact">
  <h1>Contact Information</h1>
    <ul>
    <li>
    <p>Nate Roylance</p>
    </li>
    <li>
    <p>Email - <button id='email' title='Copy' @mouseleave="leaveHover('email')" @click="doCopy('email')">natehroylance@gmail.com</button></p>
    </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Contact',
  data: function () {
    return {
    }
  },
  methods: {
    doCopy: function (elementID) {
      let str = document.getElementById(elementID).innerHTML;
      this.$copyText(str);
      document.getElementById(elementID).title = "Copied!";
    },
    leaveHover: function (elementID) {
      document.getElementById(elementID).title = "Copy";
    }
  }
}
</script>

<style scoped>
p {
  margin-top: 30px;
  font-size: 1.8rem;
}
button, input {
  border: none;
  border-radius: 10px;
  padding: 0px 10px;
  background-color: white;
  color: #438f69;
  box-shadow: 0 0px 1px 0 rgba(0,0,0,0.24), 0 0px 3px 0 rgba(0,0,0,0.19);
}
button:hover, input:hover {
  color: #438f69;
  box-shadow: 0 0px 1px 0 rgba(0,0,0,0.24), 0 0px 10px 0 rgba(0,0,0,0.19);
}
button:active, input:active {
  box-shadow: 0 0px 1px 0 rgba(0,0,0,0.24), 0 0px 3px 0 rgba(0,0,0,0.19);
}
button:focus, input:focus {
  outline:0;
}
button[title]:hover:after {
  content: attr(title);
  position: absolute;
  color: lightgray;
  transform: translate(10px, 5px);
  font-size: 1.5rem;
  padding-left: 15px;
}
</style>
