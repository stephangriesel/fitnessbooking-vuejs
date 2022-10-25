<template>
  <div class="hello">
    <!-- <h1>{{ msg }}</h1> -->
    <div class="block">
      <header>
        <nav>
          <div>Logo</div>
          <div>
            <ul>
              <li>Home</li>
              <li>About</li>
              <li>Contact</li>
            </ul>
          </div>
        </nav>
      </header>
      <section>
        <div>left</div>
        <div>right</div>
      </section>

      <footer>
        <div>
          <ul>
            <li>Home</li>
            <li>About</li>
            <li>Contact</li>
          </ul>
        </div>
        <div>
          <ul>
            <li>Reschedule</li>
            <li>Cancellation</li>
            <li>Refund</li>
          </ul>
        </div>
        <div>
          <ul>
            <li>Amsterdam</li>
            <li>Berlin</li>
            <li>London</li>
          </ul>
        </div>
      </footer>
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
h1,
h2 {
  font-weight: normal;
}

a {
  color: #42b983;
}

nav{
  display:flex;
  justify-content: space-between;
}

section{
  display:flex;
  justify-content: space-between;
}

footer{
  display: flex;
  justify-content: space-evenly;
}
</style>
