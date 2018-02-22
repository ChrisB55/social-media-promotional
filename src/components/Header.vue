<template>
<div class="container">
  <v-navigation-drawer app>{{title}}</v-navigation-drawer>
  <v-toolbar app>{{title}}</v-toolbar>
  </div>
</template>


<script>
export default {
data () {
    return {
      title: 'Polling app'
    }
  }
  }
</script>


<style>
.container {
    flex:0%;
    margin: 3em;
}
</style>


