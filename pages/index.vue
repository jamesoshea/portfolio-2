<template>
  <div class="padded-content">
    <Header />
      <About />
      <Projects />
      <Links />
      <p class="text-center text-small">Built with Vue.js and Nuxt.js</p>
  </div>
</template>

<script>
import Header from "../components/Header.vue";
import MainCard from "../components/MainCard.vue";
import About from "../components/About.vue";
import Projects from "../components/Projects.vue";
import Links from "../components/Links.vue";

export default {
	name: "Index",
	components: {
		Header,
		MainCard,
		About,
		Projects,
		Links,
	},
	data() {},
};
</script>

<style>
.portfolio__main-container {
}
</style>
