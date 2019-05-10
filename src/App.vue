<template>
  <v-app dark>
    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data () {
    return {
      //
    }
  }
}
</script>


<style>
body {
    margin: 0;
    padding: 0;
    overflow: hidden;
}
    html{
      overflow-y: hidden;
    }
</style>
