<template>
  <div>
      Hello Sam
      <div>
          <input 
          v-model="InitialCurrency"
          type="number" 
          name="InitialCurrency" 
          id="InitialCurrency">
      </div>
  </div>

</template>

<script lang="ts">
import Vue from 'vue';

export default Vue.extend({
  name: 'Currency',
  data() {
      return {
          InitialCurrency: 2
          name: 'samuel'
      };
  },
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>
