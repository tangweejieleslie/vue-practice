<template>
  <div class="hello">
    <p>Hello This is an App</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro natus, repellat soluta beatae voluptatum cumque tenetur saepe cum aliquid, nobis voluptates libero excepturi hic, vero harum provident eligendi illo nam.</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro natus, repellat soluta beatae voluptatum cumque tenetur saepe cum aliquid, nobis voluptates libero excepturi hic, vero harum provident eligendi illo nam.</p>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.hello{
  width: 50vw;
  margin: 5px;
  padding: 10px;
  background: #efefef;
  height: 100%;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
