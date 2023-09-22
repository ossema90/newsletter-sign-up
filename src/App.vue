<template>
  <v-app class="main-container   ">
    <v-main class="center">
      <HelloWorld />
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
}
</script>

<style scoped>
.main-container {
  background-color: #3b3e59;



}

.center {
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
