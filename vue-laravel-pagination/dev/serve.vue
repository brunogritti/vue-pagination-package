<script>
import Vue from 'vue';
import VueLaravelPagination from '@/vue-laravel-pagination.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    VueLaravelPagination
  }
});
</script>

<template>
  <div id="app">
    <vue-laravel-pagination />
  </div>
</template>
