<template>
  <v-content>
    <v-container fluid class="fill-height login-container">
      <v-row wrap justify="center" align="center">
        <v-col cols="12" md="8" xs="12" lg="4">
          <AdminLogin />
        </v-col>
      </v-row>
    </v-container>
  </v-content>
</template>

<script lang="ts">
import Vue from 'vue';
import AdminLogin from '~/components/admin-login/AdminLogin.vue';

export default Vue.extend({
  components: {
    AdminLogin
  }
});
</script>

<style lang="scss" scoped>
.main-logo{
  width:80%;
  height:auto;
}
.login-container{
  background-image:linear-gradient(#7cddcd,#ff0850);
}
</style>
