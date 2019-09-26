<template>
  
<v-app>

<Home/>
<About/>
<Classes/>

</v-app>

</template>

<script>
import Home from './Home';
import About from './About';
import Classes from './Classes';

export default {
     components: {
    Home,
    About,
    Classes
  },

}
</script>

<style>

</style>