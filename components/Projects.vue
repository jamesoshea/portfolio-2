<template>
  <div>
    <div id="about" class="ff-card padding-small text-justify margin-top-tiny">
      <h4>Projects</h4>
      <div class="row">
        <div class="portion one-fourth">
          <a href="https://github.com/3YOURMIND/fire-pr">Fire-PR</a>
        </div>
        <div class="portion two-fourths">
          A tool we created at 3YOURMIND to standardise Pull Requests by
          providing a standard template, and auto filling it using a
          chrome extension written in Vue.
        </div>
        <div class="portion one-fourth">
          November 2017<br />
          -<br />
          Present<br />
        </div>
      </div>
      <div class="row">
        <div class="portion one-fourth">
          <a href="https://github.com/jamesoshea/touchemin">Touchemin</a>
        </div>
        <div class="portion two-fourths">
          A Vue based PWA which uses Tone.js to play chords based on touch
          screen interactions. Implements a filter and settings are coming
          soon.
        </div>
        <div class="portion one-fourth">
          April 2018<br />
          -<br />
          Present<br />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
	name: "About",
};
</script>

<style>
.text-justify {
	text-align: justify;
}
.portfolio-border-bottom {
	border-bottom: 1px solid rgba(0, 0, 0, 0.04);
}
</style>
