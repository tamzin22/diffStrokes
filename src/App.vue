<template>
  <div id="app" class="container-fluid">
    <meta name="viewport" content="width=device-width, initial-scale=1" user-scalable="no">
  <div container p-3 my-3 border>
  <home />
  <about/>
  <description />
  <services />
  <offers/>
  <formFill/>
  <offers />
  <closing />
   </div></div>
</template>

<script>
import home from './components/home.vue'
import about from './components/about.vue'
import services from './components/services.vue'
import description from './components/description.vue'
import offers from './components/offeredServices.vue'
import FormFill from './components/formFill.vue'
import Closing from './components/closing.vue'




export default {
  name: 'App',
  components: {
    home,
    about,
    services,
    description,
    offers,
    FormFill,
    Closing,
    
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
.full-width-div {
    width: 100%;
    left: 0;
}

</style>
