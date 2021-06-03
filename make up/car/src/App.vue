<template>
  <v-app>
    <banner/>
    <first/>
<div class='div-extra-app1'/>
    <props/>
    <div class='div-extra-app1'/>
    <news/>
    <fotter/>
  </v-app>
</template>

<script>
import first from'./components/first';
import banner from './components/banner';
import props from './components/props';
import news from './components/news';
import fotter from './components/fotter'
export default {
  name: 'App',

  components: {
    banner,
    first,
    props,
    fotter,
    news,
  },

  data: () => ({
    //
  }),
};


</script>
<style scoped>
.div-extra-app1
{
padding-top:10vw ;
}
</style>