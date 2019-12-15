<template>
  <v-container>
    <v-card p-4 elevation="24">
      <v-row wrap align-content="center" justify="center">
        <v-col cols="12">
          <ArkavidiaLoginImage class="my-2" />
        </v-col>
        <v-col cols="12">
          <AdminLoginHeader />
        </v-col>
        <v-col cols="12">
          <v-card-text>
            <LoginForm />
          </v-card-text>
        </v-col>
      </v-row>
    </v-card>
  </v-container>
</template>

<style lang='scss' scoped>

</style>

<script lang='ts'>
import Vue from 'vue';
import LoginForm from './LoginForm.vue';
import ArkavidiaLoginImage from './ArkavidiaLoginImage.vue';
import AdminLoginHeader from './AdminLoginHeader.vue';

export default Vue.extend({
  name: 'AdminLogin',
  components: {
    LoginForm,
    ArkavidiaLoginImage,
    AdminLoginHeader
  }
});
</script>
