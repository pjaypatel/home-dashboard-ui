// App.vue

<template>
  <Dashboard></Dashboard>
</template>

<script>
import Dashboard from './components/Dashboard'

export default {
  data () {
    return {
      clipped: false,
      drawer: true,
      fixed: false,
      items: [{
        icon: 'bubble_chart',
        title: 'Inspire'
      }],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Vuetify.js'
    }
  },
  name: 'App',
  components: {
    Dashboard
  }
}
</script>
