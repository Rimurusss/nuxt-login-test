<template>
  <v-container class="fill-height" fluid>
    <v-row align="center" justify="center" dense>
      <v-col cols="12" sm="8" md="4" lg="4">
        <v-card elevation="0">
          <div class="text-center">
            <p class="mb-2 text-4xl">Login</p>
          </div>
          <a
            href="https://assets.reedpopcdn.com/Genshin-Impact-anime.jpg/BROK/thumbnail/1600x900/quality/100/Genshin-Impact-anime.jpg"
            name="Fedorae Education"
            title="Fedorae Education"
            target="_blank"
          >
            <v-img
              src="https://i.pinimg.com/originals/b9/43/e3/b943e3b6eabdd3e31b681ef13a9872a0.png"
              alt="Fedorae Education Log"
              contain
              height="200"
            ></v-img>
          </a>
          <v-card-text>
            <v-form>
              <v-text-field
                label="Enter your email"
                name="email"
                prepend-inner-icon="mdi-email"
                type="email"
                class="rounded-0"
                outlined
              ></v-text-field>
              <v-text-field
                label="Enter your password"
                name="password"
                prepend-inner-icon="mdi-lock"
                type="password"
                suffix="| Forgot?"
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
                >Login</v-btn
              >
              <v-card-actions class="text--secondary">
                <v-checkbox color="#000000" label="Remember me"></v-checkbox>
                <v-spacer></v-spacer>
                No account?
                <a href="signup" class="pl-2" style="color: #000000">Sign Up</a>
              </v-card-actions>

            
                <v-btn class="mx-2 mb-2" @click="login-google">
                  <v-icon class="mx-2" size="30"> mdi-google </v-icon>
                  signup with google
                </v-btn>
                <v-btn class="mx-2 mb-2" @click="login-facebook">
                  <v-icon class="mx-2" size="30"> mdi-facebook </v-icon>
                  signup with facebook
                </v-btn>
                <v-btn class="mx-2 mb-2" @click="login-discord">
                  <v-icon class="mx-2" size="30"> mdi-google </v-icon>
                  signup with discord
                </v-btn>
                <v-btn class="mx-2 mb-2" @click="login-githud">
                  <v-icon class="mx-2" size="30"> mdi-google </v-icon>
                  signup with githud
                </v-btn>

            </v-form>
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>


<!-- <template>
    <v-layout align-center justify-center>
    <v-card class="pa-5">
      <v-layout align-center justify-center column>
        <v-layout align-center justify-center row>
          <v-divider width="100" />
          <v-subheader class="overline">
            TIME SHEET LOGIN
          </v-subheader>
          <v-divider width="100" />
        </v-layout>
        <v-btn class="mx-2 mb-2" @click="login">
          <v-icon class="mx-2" size="30">
            mdi-google
          </v-icon>
          signup with google
        </v-btn>
      </v-layout>
    </v-card>
  </v-layout>
</template> -->
<script>
export default {
  layout: 'CoreLayout',


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