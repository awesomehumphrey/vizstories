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
        dense
        class="grey lighten-4"
      >
        <template>
          <v-layout
            row
            align-center
          >
            <v-flex xs6>
              <v-subheader>
                Data
              </v-subheader>
            </v-flex>
          </v-layout>
          <v-list-tile
            @click=""
          >
            <v-list-tile-content>
              <v-list-tile-title class="grey--text">
                Data input
              </v-list-tile-title>
            </v-list-tile-content>
          </v-list-tile>
          <v-divider
            dark
            class="my-3"
          ></v-divider>
          <v-subheader>
            Measures
          </v-subheader>
        </v-flex>
      </v-layout>
      <v-list-tile
        @click=""
      >
        <v-list-tile-content>
          <v-list-tile-title class="grey--text">
            Measures Dropdown
          </v-list-tile-title>
        </v-list-tile-content>
      </v-list-tile>
      <v-divider
        dark
        class="my-3"
      ></v-divider>
      <v-subheader>
        Dimensions
      </v-subheader>
    </v-flex>
  </v-layout>
  <v-list-tile
    @click=""
  >
    <v-list-tile-content>
      <v-list-tile-title class="grey--text">
        Dimensions Dropdown
      </v-list-tile-title>
    </v-list-tile-content>
  </v-list-tile>
  <v-divider
    dark
    class="my-3"
  ></v-divider>
        </template>
      </v-list>
    </v-navigation-drawer>
    <v-toolbar color="amber" app absolute clipped-left>
      <v-toolbar-side-icon @click.native="drawer = !drawer"></v-toolbar-side-icon>
      <span class="title ml-3 mr-5">Gravity++</span></span>
      <v-spacer></v-spacer>
    </v-toolbar>
    <v-content>
      <v-container fluid fill-height class="grey lighten-4">
        <v-layout justify-center align-center>
          <v-flex shrink>

          </v-flex>
        </v-layout>
      </v-container>
    </v-content>
  </v-app>
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
