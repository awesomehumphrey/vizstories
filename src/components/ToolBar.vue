<template>
  <v-toolbar color="blue lighten-5" app absolute clipped-left>
    <v-toolbar-side-icon @click.native="drawer = !drawer"></v-toolbar-side-icon>
    <span class="title ml-3 mr-5 ">Gravity++</span></span>
    <v-spacer></v-spacer>
  </v-toolbar>
</template>

<script>
export default {
  data: () => ({
    drawer: null,
  }),
  props: {
    source: String
  }
}

</script>

<style>

</style>
