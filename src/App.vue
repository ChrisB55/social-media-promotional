<template>
  <v-app>
<app-header></app-header>
    <app-home></app-home>
    <v-footer :fixed="fixed" app>
      <span>&copy; {{id}}</span>
    </v-footer>
  </v-app>
</template>

<script>

import Home from './components/Home.vue';
import Header from './components/Header.vue';

export default {
  components: {
    appHome: Home,
    appHeader: Header,
    
  },
  data () {
    return {
      id: '2017 Publica Now Digitial Services'
    }
  },
  name: 'App'
}
</script>
