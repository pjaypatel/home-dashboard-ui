<template>
  <div>
    <button v-on:click="playing=true">
      Play
    </button>
    <div class="margin"/>
    <button v-on:click="playing=false">
      Pause
    </button>
  </div>
</template>
<script>
export default {
  name: "Music",
  data: function () {
    return {
      playing: false
    }
  }
}
</script>
<style>
.margin {
  margin: 2px
}
</style>
