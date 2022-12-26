<template>
  <div>
    <MenuTop />
    <router-view />
    <FooterBottom />        
    
  </div>
  


  <!--  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav> -->



</template>

<script setup>
import MenuTop from "@/components/templates/MenuTop.vue";
import FooterBottom from "@/components/templates/FooterBottom.vue";


/* export default {

  components:{
    MenuTop,
    FooterBottom
  }
} */
</script>