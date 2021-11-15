<script>
import Vue from 'vue';
import TestComponent from '@/test-component.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    TestComponent
  }
});
</script>

<template>
  <div id="app">
    <test-component />
  </div>
</template>
