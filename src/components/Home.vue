<template>
  <div class="hello">
    <!-- <h1>{{ msg }}</h1> -->
    <div class="block">
      <header>
        <nav>
          <div class="logo">Logo</div>
          <div class="menu">
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
          <h2>Sitemap</h2>
          <ul>
            <li>Home</li>
            <li>About</li>
            <li>Contact</li>
          </ul>
        </div>
        <div>
          <h2>Classes</h2>
          <ul>
            <li>Reschedule</li>
            <li>Cancellation</li>
            <li>Refund</li>
          </ul>
        </div>
        <div>
          <h2>Locations</h2>
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

html, body {
  margin:0;
  padding:0;
}
h1,
h2 {
  font-weight: normal;
}

a {
  color: #42b983;
}

ul {
  list-style: none;
}

nav{
  display:flex;
  justify-content: space-evenly;
  flex-wrap:wrap;
}

nav ul {
  padding:0;
}

.logo {
  display:flex;
  align-items: center;
  justify-content: center;
}
.menu ul {
  display:flex;
  align-items: center;
}

.menu li {
  margin:1rem;
}

section{
  display:flex;
  justify-content: center;
  flex-wrap: wrap;
}

@media only screen and (max-width: 500px){
  /* TO DO: child element 1 */
  section {
    display:flex;
    flex-direction: column-reverse;
  }
}

.block {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.block p {
  margin:2rem;
}

footer{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-evenly;
  background-color:lightgray;
  margin:2rem 0;
  padding:0;
}

footer ul {
  padding: 0;
  margin:1rem 3rem;
}

footer li {
  margin:0.5rem 0;
}

</style>
