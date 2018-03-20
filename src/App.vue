<template>
  <v-app id="inspire">
    <v-navigation-drawer
      fixed
      clipped
      class="grey lighten-4"
      app
      v-model="drawer"
    >
      <v-list
      >
        <app-tabs></app-tabs>
      </v-list>
    </v-navigation-drawer>
    <app-toolbar></app-toolbar>
    <app-content></app-content>
  </v-app>
</template>

<script>
  import Tabs from './components/Tabs.vue';
  import ToolBar from './components/ToolBar.vue';
  import Content from './components/Content.vue';

  export default {
    components: {
            'app-tabs': Tabs,
            'app-toolbar': ToolBar,
            'app-content': Content
        },
    data: () => ({
      drawer: null,
    }),
    props: {
      source: String
    }
  }
</script>

<style scoped>
  #keep main .container {
    height: 660px;
  }
  .navigation-drawer__border {
    display: none;
  }
  .text {
    font-weight: 400;
  }
</style>
