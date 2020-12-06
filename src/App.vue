<template>
  <div id="app" class="container-fluid">
  <div container p-3 my-3 border>
  <home />
  <about/>
  <description />
  <services />
    </div>
   </div>
</template>

<script>
import home from './components/home.vue'
import about from './components/about.vue'
import services from './components/services.vue'
import description from './components/description.vue'




export default {
  name: 'App',
  components: {
    home,
    about,
    services,
    description,
    
  }
}
</script>

import default{

}

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
 
}

</style>
