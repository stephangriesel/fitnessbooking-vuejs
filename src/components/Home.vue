<template>
  <div class="hello">
    <!-- <h1>{{ msg }}</h1> -->
    <div class="block">
      <div>left</div>
      <div>right</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Home'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
a {
  color: #42b983;
}
.block {
  display:flex;
  justify-content: space-evenly;
  align-items: center;
}
</style>
