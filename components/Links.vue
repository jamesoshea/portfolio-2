<template>
  <div class="ff-card padding-small text-justify margin-top-tiny margin-bottom-tiny">
    <h4>Links</h4>
    <div class="row">
      <LinkCard :linkUrl="'http://github.com/jamesoshea'">
        <GithubSVG />
      </LinkCard>
      <LinkCard :linkUrl="'mailto:j@mesoshea.com'">
        <MailSVG />
      </LinkCard>
      <LinkCard :linkUrl="'https://medium.com/@james_oshea'">
        <MediumSVG />
      </LinkCard>
    </div>
  </div>
</template>

<script>
import LinkCard from "../components/LinkCard.vue";
import GithubSVG from "../components/GithubSVG.vue";
import MailSVG from "../components/MailSVG.vue";
import MediumSVG from "../components/MediumSVG.vue";

export default {
	name: "Links",
	components: {
		LinkCard,
		GithubSVG,
		MailSVG,
		MediumSVG,
	},
};
</script>

<style>
</style>
