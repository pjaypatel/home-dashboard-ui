<template>
  <v-content>
    <v-container>
      <v-layout row wrap>
        <v-flex xs6>
          <v-card dark color="primary">
            <v-card-text class="px-0">
              <h1>Hello World</h1>
            </v-card-text>
          </v-card>
        </v-flex>
        <v-flex xs6>
          <v-card dark color="primary">
            <v-card-text class="px-0">
              <h1>Hello World</h1>
            </v-card-text>
          </v-card>
        </v-flex>
        <Clock>
        </Clock>
      </v-layout>
    </v-container>
  </v-content>
</template>
<script>
import Clock from './Clock.vue'

export default {
  name: 'Dashboard',
  components: {
    Clock
  }
}
</script>
<style>
</style>
