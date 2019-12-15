<template>
  <v-content>
    <v-container fluid class="fill-height">
      <v-row wrap justify="center" align="center">
        <v-col cols="12" sm="8" md="4">
          <v-card raised p-4>
            <v-row align="center" justify="center">
              <v-col cols="10" align="center">
                <img src="~/assets/logo-horz.svg" class="justify-center main-logo">
              </v-col>
            </v-row>
            <v-list-item three-line>
              <v-list-item-content>
                <v-list-item-title class="headline mb-1" align="center">
                  Login
                </v-list-item-title>
                <v-list-item-subtitle align="center">
                  Enter your login credentials.
                </v-list-item-subtitle>
              </v-list-item-content>
            </v-list-item>
            <v-card-text>
              <v-form>
                <v-text-field label="Username" type="text" />
                <v-text-field label="Password" type="password" />
                <v-row class="text-center">
                  <v-col cols="12">
                    <v-btn raised color="success" class="mx-4 px-12">
                      Login
                    </v-btn>
                  </v-col>
                  <v-col cols="12">
                    <p>Not yet registered? <a>Register.</a>
                    </p>
                  </v-col>
                </v-row>
              </v-form>
            </v-card-text>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </v-content>
</template>

<script lang="ts">

</script>

<style lang="scss" scoped>
.main-logo{
  width:80%;
  height:auto;
}
</style>
