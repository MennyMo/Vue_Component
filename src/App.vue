<template>
  <div id="app">
    <NavBar />
    <Main />
    <MainButton />
    <SectionOne />
    <SectionTwo />
    <SectionThree />
    <SectionFour />
    <Footer/>
     <!-- <template #name>
       HI there
    </template> -->
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import Main from './components/Main.vue'
import MainButton from './components/MainButton.vue'
import SectionOne from './components/SectionOne.vue'
import SectionTwo from './components/SectionTwo.vue'
import SectionThree from './components/SectionThree.vue'
import SectionFour from './components/SectionFour.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    NavBar,
    Main,
    MainButton,
    SectionOne,
    SectionTwo,
    SectionThree,
    SectionFour,
    Footer 
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700&display=swap');
#app {
  font-family: 'Poppins', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 20px;
}
@import '~bootstrap/dist/css/bootstrap.min.css'
</style>
