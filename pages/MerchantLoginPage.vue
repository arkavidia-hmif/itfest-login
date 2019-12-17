<template>
  <v-content class="login-container">
    <v-container class="fill-height" fluid pa-12>
      <MerchantLogin />
    </v-container>
  </v-content>
</template>

<style lang="scss" scoped>

</style>

<script lang="ts">
import Vue from 'vue';
import MerchantLogin from '~/components/merchant-login/MerchantLogin.vue';

export default Vue.extend({
  components: {
    MerchantLogin
  }
});
</script>
