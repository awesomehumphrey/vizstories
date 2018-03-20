<template>
  <v-tabs
  v-model="active"
  color="blue lighten-5"
  dark
  slider-color="yellow"
>
  <v-tab
    class="black--text"
    ripple
  >
    Data
  </v-tab>
  <v-tab-item
  >
    <template>
    <v-layout
      row
      align-center
    >
      <v-flex xs6>
        <v-subheader class="black--text">
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
    <v-layout
      row
      align-center
    >
    <v-flex xs6>
    <v-subheader class="black--text">
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
<v-layout
  row
  align-center
>
<v-flex xs6>
<v-subheader class="black--text">
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
  </v-tab-item>
 <v-tab
  class="black--text"
    ripple
  >
    Story
  </v-tab>
  <v-tab-item
  >
    <v-card flat>
      <v-card-text>Stories here</v-card-text>
    </v-card>
  </v-tab-item>
</v-tabs>
</template>

<script>
</script>

<style>

</style>
