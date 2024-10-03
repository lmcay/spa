<template>
  <div id="app">
    <about></about>
    <profile></profile>
    <education></education>
    <skills></skills>
  </div>
</template>

<script>

import profile from './components/profile.vue';
import education from './components/education.vue';
import skills from './components/skills.vue';

export default {
  name: 'app',
  components: {
    profile,
    education,
    skills
  }
}

</script>