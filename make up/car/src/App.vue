<template>
  <v-app>
    <banner/>
    <first/>
    <props/>
  </v-app>
</template>

<script>
import first from'./components/first';
import banner from './components/banner';
import props from './components/props';
export default {
  name: 'App',

  components: {
    banner,
    first,
    props,
  },

  data: () => ({
    //
  }),
};


</script>
