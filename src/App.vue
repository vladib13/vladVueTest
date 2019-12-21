<template>
  <div id="app">
    <Header/>
    <CoverPage/>
    <BodySection/>
    <EndSection/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import CoverPage from './components/CoverPage.vue';
import BodySection from './components/BodySection.vue';
import EndSection from './components/EndSection.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'app',
  components: {
    Header,
    CoverPage,
    BodySection,
    EndSection,
    Footer
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  color: #2c3e50;
}
</style>
