<script>
import axios from 'axios';
import { store } from '../store';
import AppComponent from './AppComponent.vue';

export default {
    data() {
        return {
        store,
        };
    },
    methods: {

    },
    components: {
        AppComponent,
    },

}
</script>

<template>
  <div>
    <AppComponent/>
  </div>
</template>

<style lang="scss" scoped>
</style>
