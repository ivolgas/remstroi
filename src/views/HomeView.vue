<template>
  <div class="home">    
    <PageView msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import PageView from './PageView.vue'

export default {
  name: 'HomeView',
  components: {    
    PageView
}
}
</script>
