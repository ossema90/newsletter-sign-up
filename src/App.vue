<template>
  <v-app class="main-container ">
    <v-main style="top:0; bottom:0;">
      <HelloWorld class="d-flex justify-center  mt-16 " />
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
</style>
