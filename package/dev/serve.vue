<script lang="ts">
import Vue from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { TestPackageSample } from '@/entry.esm';

export default Vue.extend({
  name: 'ServeDev',
  // components: {
  //  TestPackageSample,
  // }
});
</script>

<template>
  <div id="app">
    <h1>Hello!</h1>
    <test-package-sample />
  </div>
</template>
