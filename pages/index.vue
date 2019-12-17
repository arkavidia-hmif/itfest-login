<template>
  <v-layout>
    <v-content>
      <v-container fluid class="fill-height login-container">
        <v-row wrap justify="center" align="center">
          <v-col cols="4" md="6" xs="12" lg="4">
            <nuxt-link to="/AdminLoginPage">
              <v-card class="pagecard">
                Admin Login
              </v-card>
            </nuxt-link>
          </v-col>
          <v-col cols="4" md="6" xs="12" lg="4">
            <nuxt-link to="/MerchantLoginPage">
              <v-card class="pagecard">
                Merchant Login
              </v-card>
            </nuxt-link>
          </v-col>
          <v-col cols="4" md="6" xs="12" lg="4">
            <nuxt-link to="/UserLoginPage">
              <v-card class="pagecard">
                User Login
              </v-card>
            </nuxt-link>
          </v-col>
        </v-row>
      </v-container>
    </v-content>
  </v-layout>
</template>

<style lang="scss" scoped>
.pagecard{
  height:300px;
}
.login-container{
  background-image:linear-gradient(#7cddcd,#ff0850);
}
</style>
