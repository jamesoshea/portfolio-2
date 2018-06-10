<template>
  <div class="portion one-third">
    <div class="card-content text-center">
      <a :href="`#`">
        <slot></slot>
      </a>
    </div>
  </div>
</template>

<script>
export default {
	name: "links",
};
</script>

<style>
</style>
