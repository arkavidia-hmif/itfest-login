<template>
  <v-row justify="center" justify-md="start" align="center">
    <v-col
      cols="12"
      md="6"
      lg="4"
      align-center
      justify-center
    >
      <div class="text-right headline section-title">
        Login ke Dashboard.
      </div>
    </v-col>
    <v-col
      cols="12"
      md="6"
      lg="6"
      align-center
      justify-center
    >
      <MerchantLoginForm :button-text="'Login'" />
    </v-col>
  </v-row>
</template>

<style lang="scss" scoped>
  .headline{
    font-weight: 700;
  }
  .login-container{
    background-color:#ffffff;
  }
  .section-title {
    position: relative;
    padding-bottom: 8px;
  }

  .section-title:after {
    content: "";
    position: absolute;
    width: 100px;
    height: 1px;
    bottom: 0;
    right: 0;
    border-bottom: 4px solid #FF084F;
  }
</style>

<script>
import Vue from 'vue';
import MerchantLoginForm from './MerchantLoginForm.vue';

export default Vue.extend({
  name: 'MerchantLogin',
  components: {
    MerchantLoginForm
  }
});
</script>
