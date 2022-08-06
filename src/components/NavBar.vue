<template>
  <v-app-bar app color="#111111" dark flat class="px-8">
    <v-btn icon> 
      <v-img class="navbar-brand orange darken-1 p-5 " back="#FF8F00" href="index.html">Orun </v-img>
    </v-btn>

    <!-- <v-spacer></v-spacer> -->
    <v-btn text @click="scroll('home')">Home</v-btn>
    <v-btn text @click="scroll('project')">Project</v-btn>
    <v-btn text @click="scroll('about')">about</v-btn>
    <v-btn text @click="scroll('contact')"> contact</v-btn>
  </v-app-bar>
</template>

<script>
export default {
  methods: {
    scroll(refName) {
      const element = document.getElementById(refName);
      element.scrollIntoView({ behavior: "smooth" });
    },
  },
};
</script>

<style>
</style>