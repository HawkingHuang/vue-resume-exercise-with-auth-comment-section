<!-- Port: 1003 -->
<template>
  <div>
    <login />
    <HeaderSection />
    <IntroSection />
    <Degree />
    <Skills />
    <WorkExp />
    <LanguagePerk />
    <Portfolio />
  </div>
</template>

<script>
import Login from "./components/Login.vue";
import HeaderSection from "./components/HeaderSection.vue";
import IntroSection from "./components/IntroSection.vue";
import Degree from "./components/Degree.vue";
import Skills from "./components/Skills.vue";
import WorkExp from "./components/WorkExp.vue";
import LanguagePerk from "./components/LanguagePerk.vue";
import Portfolio from "./components/Portfolio.vue";

export default {
  name: "App",
  components: {
    Login,
    HeaderSection,
    IntroSection,
    Degree,
    Skills,
    WorkExp,
    LanguagePerk,
    Portfolio,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;500;600;700&display=swap");
* {
  font-family: "Quicksand", sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  font-size: 62.5%;
  background: #dee2e6;
}

.section {
  background: white;
  padding: 1.2rem 2rem;
  border-radius: 10px;
}
</style>
