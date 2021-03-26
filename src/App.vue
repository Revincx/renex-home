<template>
  <Corner/>
  <Central/>
</template>

<script>
import Central from "./components/Central.vue";
import Corner from "./components/Corner.vue";

export default {
  name: 'App',
  components: {
    Central,
    Corner
  }
}
</script>

<style>

body{
  background: #FFE4E1;
}

</style>
