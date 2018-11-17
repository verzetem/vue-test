<template>
  <div class="hello">
    <h1>{{ helloProps }}</h1>
    <img src="https://cdn-img.health.com/sites/default/files/styles/large_16_9/public/styles/main/public/gettyimages-522881398.jpg"/>
    <img src="https://fortunedotcom.files.wordpress.com/2017/08/512536165-e1510081190643.jpg"/>
    <img src="https://cpb-us-w2.wpmucdn.com/u.osu.edu/dist/2/8857/files/2015/04/puppies3-1ai51q6.jpg"/>
    <img src="https://i.kinja-img.com/gawker-media/image/upload/s--vaC0BSO_--/c_scale,f_auto,fl_progressive,q_80,w_800/l8bricwb5lg4fcisxvjh.jpg"/>
    <img src="https://static.inspiremore.com/wp-content/uploads/2013/10/23065406/pup1.jpg"/>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    helloProps: String
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
img {
  width: 19%;
  margin-top: 1%;
  margin-right: 0.5%;
  border-radius: 100px;
  border: solid 1px gray;
}
img:hover {
  width: 25%;
}
</style>
