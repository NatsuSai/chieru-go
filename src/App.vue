<template>
  <v-app>
    <v-app-bar
      app
      color="#cb62b4"
      dark
      dense
    > 
    切噜语翻译
    <v-spacer></v-spacer>
     <v-btn   text class="text-white" target="_blank" 
        href="https://github.com/NatsuSai/cheru-go">github
        <v-icon small>mdi-open-in-new</v-icon>
        </v-btn>
    </v-app-bar>
    <v-content >
      <Chieru/>
    </v-content>
  </v-app>
</template>

<script>
import Chieru from './components/Chieru';

export default {
  name: 'App',
  components: {
    Chieru: Chieru,
  },
  data: () => ({
    //
  }),
};
</script>
<style >
  .v-input__append-inner{
    align-self: start !important;
    margin-top:10px !important;
  }
</style>
