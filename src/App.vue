<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import axios from 'axios';
import { store } from './store';


export default {
    data() {
        return {
          store,
        };
    },
    components: {
        AppHeader,
        AppMain,
        AppFooter
    },  
    methods: {

    }
}
</script>

<template>
  <div>
    <h1>
        Mia App
    </h1>

    <AppHeader />
    <AppMain />
    <AppFooter />
  </div>
</template>

<style lang="scss">
@use "assets/scss/main" as *;
@import "assets/scss/partials/reset";
</style>
