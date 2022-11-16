<template>
  <v-container class="fill-height" fluid>
    <v-row align="center" justify="center" dense>
      <v-col cols="12" sm="8" md="4" lg="4">
        <v-card elevation="0">
          <div class="text-center">
            <p class="mb-2 text-4xl">Sign Up</p>
          </div>
          
          <v-card-text>
            <v-form>
              <v-text-field
                label="Enter your Name"
                name="email"
                type="email"
                class="rounded-0"
                outlined
              ></v-text-field>
              <v-text-field
                label="Enter your email"
                name="email"
                type="email"
                class="rounded-0"
                outlined
              ></v-text-field>
              <v-text-field
                label="Enter your password"
                name="password"
                type="password"
                class="rounded-0"
                outlined
              ></v-text-field>
              <v-text-field
                label="Enter your password"
                name="password"
                type="password"
                class="rounded-0"
                outlined
              ></v-text-field>
              <v-btn
                class="rounded-0"
                color="#000000"
                x-large
                block
                dark
                to="/home"
                >Sign Up</v-btn
              >

            </v-form>
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  layout: "CoreLayout",
};
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>