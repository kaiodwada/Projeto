<template>
<v-app id="inspire">
 <v-container ma-0 pa-0 fluid="">

 <AppHeader class="menu"/> 
 <router-view></router-view>

<AppFooter/>
 </v-container>

    </v-app>
</template>

<script>

import AppHeader from './components/AppHeader';
import AppFooter from './components/AppFooter';


export default {
  components: {
    AppHeader,
    AppFooter,
  },
  }
</script>


<style>
  html, body, #app {
 margin: 0;
 padding: 0;
    background: #ccc;

  }

</style>
