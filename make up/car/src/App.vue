<template>
  <v-app>
    <banner/>
    <first/>
    <props/>
    <fotter/>
  </v-app>
</template>

<script>
import first from'./components/first';
import banner from './components/banner';
import props from './components/props';
import fotter from './components/fotter'
export default {
  name: 'App',

  components: {
    banner,
    first,
    props,
    fotter,
  },

  data: () => ({
    //
  }),
};


</script>
