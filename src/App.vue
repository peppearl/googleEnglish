<template>
  <Header/>
  <div id="googleSearch">
    <img id="googleLogo" alt="Google logo" src="./assets/google.gif">
    <GoogleSearch @scrollto="goto('goals')" />
  </div>
  <div ref="goals" id="googleGoals">
    <Goals/>
  </div>
  <div ref="hire" id="googleHire">
    <Hire/>
  </div>
  <div ref="work" id="googleWork">
    <Work/>
  </div>
</template>

<script>
import GoogleSearch from './components/GoogleSearch.vue'
import Header from './components/Header.vue'
import Goals from "./components/Goals";
import Hire from "./components/Hire";
import Work from "./components/Work";

export default {
  name: 'App',
  components: {
    Work,
    Hire,
    GoogleSearch,
    Header,
    Goals
  },
  methods: {
    goto(refName) {
      let element = this.$refs[refName];
      let top = element.offsetTop;
      //window.scrollTo(0, top);
      window.scrollTo({
        top: top,
        left: 0,
        behavior: 'smooth'
      });
    }
  }
}
</script>

<style>
#app {
  font-family: Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

#googleLogo {
  margin-bottom: 38px;
}

#googleSearch {
  height: 100vh;
}

#googleSearch {
  text-align: center;
}

#googleGoals, #googleHire, #googleWork {
  margin-left: 180px;
  width: 652px;
  margin-bottom: 30px;
}
</style>
