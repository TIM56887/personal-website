<template>
  <div id="app">
    <NavBar />
    <PortfolioResume />
    <PortfolioList />
    <LearningResource />
    <CommentSection />
    <AboutMe />
  </div>
  
</template>

<script>
import PortfolioResume from './components/PortfolioResume.vue'
import PortfolioList from './components/PortfolioList.vue'
import CommentSection from './components/CommentSection.vue'
import LearningResource from './components/LearningResource.vue';
import AboutMe from './components/AboutMe.vue';
import NavBar from './components/NavBar.vue'
import "animate.css";
// import HousePrice from './components/HousePrice.vue';
export default {
  name: 'App',
  components: {
    PortfolioResume,
    LearningResource,
    AboutMe,
    CommentSection,
    PortfolioList,
    NavBar,
    // HousePrice
  },
  
  
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
  
}
.gradient-text {
        --tw-gradient-from: #60a5fa;
        --tw-gradient-to: #1d4ed8;
        --tw-gradient-stops: var(--tw-gradient-from), var(--tw-gradient-to);
        background-image: linear-gradient(to right, var(--tw-gradient-stops));
        -webkit-background-clip: text;
        background-clip: text;
        color: transparent;
        font-weight: 700;
    }

body {
  margin: 0;
  padding: 0;
}

</style>
