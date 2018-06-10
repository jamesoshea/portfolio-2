<template>
  <div class="portion one-third">
    <div class="card-content text-center">
      <a :href="linkUrl" target="blank">
        <slot></slot>
      </a>
    </div>
  </div>
</template>

<script>
export default {
	name: "LinkCard",
	props: {
		linkUrl: {
			type: String,
			required: true,
		},
	},
};
</script>

<style>
</style>
