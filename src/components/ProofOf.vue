<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      This is my first vue app!!
    </p>
  </div>
  <button class="button" v-on:click="count++">
    This button been pressed {{ count }} times.

  </button>
</template>

<script>
export default {
  name: "ProofOf",
  props: {
    msg: String,
  },
  data () {
    return {
      count: 0
      }
	}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
