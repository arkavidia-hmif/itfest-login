<template>
  <v-content>
    <v-container fluid class="fill-height">
      <v-row wrap justify="center" align="center">
        <v-col cols="12" sm="8" md="4">
          <v-card raised p-4>
            <v-row align="center" justify="center">
              <v-col cols="10">
                <v-img src="/logo_horizontal.svg" class="justify-center" />
              </v-col>
            </v-row>
            <v-list-item three-line>
              <v-list-item-content>
                <v-list-item-title class="headline mb-1">
                  Login
                </v-list-item-title>
                <v-list-item-subtitle>
                  Silakan lakukan login terlebih dahulu.
                </v-list-item-subtitle>
              </v-list-item-content>
            </v-list-item>
            <v-card-text>
              <v-form>
                <v-text-field label="Username" type="text" />
                <v-text-field label="Password" type="password" />
                <div class="text-center">
                  <v-btn raised color="success">
                    Login
                  </v-btn>
                  <v-btn raised>
                    Register
                  </v-btn>
                </div>
              </v-form>
            </v-card-text>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </v-content>
</template>

<script>

export default {
  components: {
  }
}
</script>
