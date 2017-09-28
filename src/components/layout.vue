<template>
  <div>
    <div id="main-bar">
      <app-main-bar></app-main-bar>
    </div>
    <div id="side-bar">
      <app-side-bar></app-side-bar>
    </div>
  </div>
</template>

<script>
import Mainbar from './mainbar/index'
import Sidebar from './sidebar/index'

export default {
  name: 'layout',
  data () {
  },
  components: {
    'app-main-bar': Mainbar,
    'app-side-bar': Sidebar
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#main-bar {
  float: left;
	width: 70%;
}

#side-bar {
  float: right;
	width: 30%;
}

</style>
