<template>
  <div class="padded-content">
    <Header />
      <About />
      <Projects />
      <Articles />
      <Links />
      <p class="text-center text-small">Built with Vue.js and Nuxt.js</p>
  </div>
</template>

<script>
import About from "../components/About.vue";
import Articles from "../components/Articles.vue";
import Header from "../components/Header.vue";
import Links from "../components/Links.vue";
import MainCard from "../components/MainCard.vue";
import Projects from "../components/Projects.vue";

export default {
	name: "Index",
	components: {
		About,
		Articles,
		Header,
		Links,
		MainCard,
		Projects,
	},
};
</script>
