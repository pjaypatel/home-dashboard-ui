<template>
  <v-container>
    <v-layout>
      <v-flex xs2>
        <Clock :blink='false' :displaySeconds='true'>
        </Clock>
      </v-flex>
      <v-flex xs2>
        Hello World
      </v-flex>
      <v-flex xs2>
        <Music>
        </Music>
      </v-flex>
    </v-layout>
  </v-container>
</template>
<script>
import Clock from 'vue-digital-clock'
import Music from './Music.vue'

export default {
  name: 'Dashboard',
  components: {
    Clock,
    Music
  },
  data: function () {
    return {
      counter: 0
    }
  }
}
</script>
<style>
.flex {
  background-color: #ffffff;
}
.Clock {
    background-color: #000000;
    color: #ffffff;
    margin-left: 2px;
    margin-right: 2px;
    padding-left: 2px;
    padding-right: 2px;
    font-size: 20px;
}
</style>
