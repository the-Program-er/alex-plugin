<template>
  <v-app app>
    <MyMenu ></MyMenu> 
    <!-- <v-app-bar app></v-app-bar> -->
   
   
    
    <v-main>
      <v-container>
         <!-- <SlovnikSeznam> </SlovnikSeznam> -->
        <!-- Hello World <div> aa : {{danie}}</div> -->
      </v-container>
    </v-main>
  </v-app>
</template>


<script>
import SlovnikSeznam from "./components/SlovnikSeznam.vue";
import MyMenu from "./components/Menu.vue"


export default {
  name: "app",
  data () {
    return {
      danie: "Danie",
      right: null,
    }
  },
  components: { SlovnikSeznam , MyMenu},
  created() {},
  mounted() {},
};
</script>




<style scoped>
</style>