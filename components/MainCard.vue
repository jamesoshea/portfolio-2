<template>
  <div class="portion one-third">
    <div class="card-content text-center">
      <a :href="`#${linkId}`">
        <p v-text="category"></p>
      </a>
    </div>
  </div>
</template>

<script>
export default {
	name: "MainCard",
	props: {
		category: {
			type: String,
			required: true,
		},
		linkId: {
			type: String,
			required: true,
		},
	},
};
</script>
