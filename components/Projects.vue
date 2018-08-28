<template>
  <div>
    <div id="about" class="ff-card padding-small text-justify margin-top-tiny">
      <h4 class="margin-bottom-small">Projects</h4>
      <div class="row">
        <div class="portion one-fourth">
          <a href="https://momentumm.now.sh">Momentumm- Demo</a><br />
          <a href="https://github.com/jamesoshea/momentumm">Momentumm- Code</a>
        </div>
        <div class="portion one-fourth">
          <strong>
            August 2018 - Present
          </strong>
        </div>
        <div class="portion two-fourths">
          A streak/habit tracking app with Telegram reminders built in.
          Still a work in progress, and a great learning experience throughout
          the tech stack. Built and deployed using Vue, Express, MongoDB, Docker,
          Now and TravisCI.
        </div>
      </div>
      <div class="row">
        <div class="portion one-fourth">
          <a href="https://github.com/3YOURMIND/fire-pr">Fire-PR</a>
        </div>
        <div class="portion one-fourth">
          <strong>
            November 2017 - Present
          </strong>
        </div>
        <div class="portion two-fourths">
          A tool we created at 3YOURMIND to standardise Pull Requests by
          providing a template, which can be auto-completed using a
          chrome extension written with Vue.
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
