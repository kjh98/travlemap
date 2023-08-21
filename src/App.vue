<template>
  <GoogleMap/>
  <leftSideBar/>
</template>

<script>
import GoogleMap from './components/GoogleMapVue.vue'
import leftSideBar from './components/leftSideBar.vue'

export default ({
  name: 'App',
  components: {
    GoogleMap,
    leftSideBar
  }
})
</script>