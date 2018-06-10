<template>
  <div>
    <div id="about" class="ff-card padding-small text-justify margin-top-tiny">
      <h4>Projects</h4>
        <table class="ff-table full-width padding-tiny">
          <tbody>
            <tr>
              <td><a href="https://github.com/3YOURMIND/fire-pr">Fire-PR</a></td>
              <td>
                A tool we created at 3YOURMIND to standardise Pull Requests by
                providing a standard template, and auto filling it using a
                chrome extension written in Vue.
              </td>
              <td>
                November 2017<br />
                -<br />
                Present<br />
              </td>
            </tr>
            <tr>
              <td class="text-left"><a href="https://github.com/jamesoshea/touchemin">Touchemin</a></td>
              <td class="text-justify">
                A Vue based PWA which uses Tone.js to play chord based on touch
                screen interactions. Implements a filter and settings are coming
                soon.
              </td>
              <td>
                April 2018<br />
                -<br />
                Present<br />
              </td>
            </tr>
          </tbody>
        </table>
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
