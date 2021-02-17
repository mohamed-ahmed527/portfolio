<template>
  <div style="overflow-x:0px !improtant" id="app">
    <Navbarcomp></Navbarcomp>
    <Home></Home>
    <About></About>
    <Skills></Skills>
    <Projects></Projects>
    <Contact></Contact>
    <router-view />
  </div>
</template>
<script>
import Navbarcomp from './components/NavbarComp.vue';
import Home from './components/Home.vue';
import About from './components/About.vue';
import Skills from './components/Skills.vue';
import Projects from './components/Projects.vue';
import Contact from './components/Contact.vue';
export default {
  name:"app",
  components:{Navbarcomp,Home, About, Skills, Projects, Contact}

}
</script>
<style lang="scss">
#app {
  overflow: hidden;
  background-image: url(./assets/imgs/background.png);
  background-repeat: no-repeat;
  background-size: cover;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.container{
  width: 80%;
  margin: auto;
}
@import url('https://fonts.googleapis.com/css2?family=Reggae+One&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Lobster&family=Reggae+One&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Lobster&family=Montserrat+Alternates&family=Reggae+One&display=swap');

</style>
