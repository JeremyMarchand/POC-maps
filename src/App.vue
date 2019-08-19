<template>
  <div id="app">
   <MapRegion/>
    <!--<MapDepartment/>-->
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MapRegion from './components/MapRegion.vue'
//import MapDepartment from './components/MapDepartment.vue'

export default {
  name: 'app',
  components: {
    MapRegion,
    //MapDepartment
  },
  methods: {

  },
  data(){
    return{

    }
  }
}
</script>

<style>

</style>
