<script setup>
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
import AboutMe from './components/AboutMe.vue';
import MyWorkSiteList from './components/MyWorkSiteList.vue';
</script>

<template>
 <div class="container-md">
  <header>
      <div class="row">
      <h1>Kevin Kelbach</h1>
      </div>
      <div class="row">
      <nav>
          <ul>
              <li><a >About Me</a></li>
              <li><a >My Work</a></li>
              <li><a >Contact Me</a></li>
              <li><a >Extra</a></li>
          </ul>
      </nav>
      </div>
    
  </header>

    <main>
      <AboutMe />
      <MyWorkSiteList />
    </main>
  </div>
</template>

<style scoped>
header {
  line-height: 1.5;
  background-image: url(../dist/assets/IMG_0705.jpg);
  background-size: cover;
  background-attachment: fixed;
  background-position: 100%;
  max-height: 6rem;
}

h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
  margin: 0.4rem;
  color: rgb(248, 159, 86);
}

h3 {
  font-size: 1.2rem;
}

nav {
    font-size: 1.3rem;
}

nav ul li {
    display: inline;
    padding: 0.6rem;
    position: relative;
    color: rgb(248, 159, 86);
}

</style>
