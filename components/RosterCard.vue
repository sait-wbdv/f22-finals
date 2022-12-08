<script setup>
const props = defineProps({student: {type: Object}});
</script>

<template>
  <figure>
    <img :src="'/images/roster/' + student.avatar" :alt="student.label + ' Profile Pic'">
    <figcaption>
      <aside class="badges">badges</aside>
      <header>{{student.label}}</header>
      <p>{{student.tagline}}</p>
      <footer class="social">
        
      </footer>
    </figcaption>
  </figure>
</template>