<template>
  <div id="app">
    <router-view/>
  </div>
</template>
<script>
import 'bootstrap/dist/css/bootstrap.css'
import 'font-awesome/css/font-awesome.css'
export default {
  name: 'app',
  data: function () {
    return {
      prefixes: ['Air', 'jet', 'Fligth'],
      sufixes: ['Hub', 'Stations', 'Mart']
    }
  }
}
</script>
