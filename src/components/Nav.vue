<template>
  <div>
    <h5>NAVBAR</h5>
    <a href="#"><button>Home</button></a>
    <a href="/puppies"><button>Puppies</button></a>
    <a href="#"><button>About</button></a>
  </div>
</template>

<script>
export default {
  name: 'NavBar',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  color: #B6E7FF;
  margin: 40px 0 0;
  font-size: 4em;
}
button {
  margin-right: 1.5%;
  background-color: #B6E7FF;
  font-size: 25px;
  border-radius: 5px;
  width: 150px;
  border: solid 2px #2B363D;
}
button:hover {
  /*color: pink;*/
  background-color: pink;
}
</style>
