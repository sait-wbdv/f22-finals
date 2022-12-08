<script setup>
const props = defineProps({link: {type: String}});
</script>

<template>
  <li><img :src="'/images/icons/' + badge.name + '.svg'" :alt="badge.name + ' Icon'" :title="badge.name"></li>
</template>