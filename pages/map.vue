<template>
  <div>
    <h3>My Google Maps Demo</h3>
      <gmap-map
        :center="{lat:10, lng:10}"
        :zoom="7"
        style="width: 500px; height: 300px"
      />
      <gmap-map
        :center="{lat:10, lng:10}"
        :zoom="7"
        style="width: 500px; height: 300px"
      />
      <gmap-map
        :center="{lat:10, lng:10}"
        :zoom="7"
        style="width: 500px; height: 300px"
      />
  </div>
</template>
<script>
import * as VueGoogleMaps from '~/node_modules/vue2-google-maps/src/main'
import Vue from 'vue'
Vue.use(VueGoogleMaps, {
  load: {
    key: 'AIzaSyCFuJFuBF3Ib7tNrjbi5parO6Gnp_-_Eq0'
  }
})
export default {
  mounted () {

  }
}
</script>
