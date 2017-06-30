<template>
  <v-app>
    <v-toolbar class="blue" light>
      <v-toolbar-title>{{title}}</v-toolbar-title>
    </v-toolbar>
  </v-app>
</template>

<script>
  export default {
    data () {
      return {
        title: 'Maxemilian Grönbloms Portfolio'
      }
    }
  }
</script>

<style lang="stylus">
  @import './stylus/main'
</style>
