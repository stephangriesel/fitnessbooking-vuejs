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
        <div>
          <img width="500" src="https://res.cloudinary.com/dvme554nj/image/upload/v1666763761/fitness-website/group_tmerrb.jpg" alt="group training">
        </div>
        <div class="block">
          <h2>Group Training</h2>
          <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nisi, eum.</p>
        </div>
      </section>
      <section>
        <div class="block">
          <h2>Running Clinics</h2>
          <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nisi, eum.</p>
        </div>
        <div>
          <img width="500" src="https://res.cloudinary.com/dvme554nj/image/upload/v1666763761/fitness-website/run_nujjxz.jpg" alt="running clinics">
        </div>
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
  justify-content: center;
  flex-wrap: wrap;
}

.block {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

footer{
  display: flex;
  justify-content: space-evenly;
}
</style>
