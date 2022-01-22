<template>
  <v-app>
    <v-app-bar app color="rgb(0, 0, 0) " class="white--text small">
      <v-app-bar-nav-icon
        color="white"
        @click="drawer = !drawer"
      ></v-app-bar-nav-icon>
      <v-toolbar-title>
        <div class="d-flex">
          <v-btn dark text href="#hello">
             <span class="code">&lt;</span>{{ msg }}<span class="code">/></span>
          </v-btn>
         
        </div>
      </v-toolbar-title>
    </v-app-bar>

    <v-navigation-drawer app v-model="drawer" temporary dark>
      <v-row class="text-center mt-5">
        <v-col cols="12">
          <v-avatar>
            <img src="./assets/cody.jpg" />
          </v-avatar>
        </v-col>
        <v-col cols="12">
          <v-btn id="btnAboutMe" href="#aboutMe" class="white--text mt-3" text>
            <span class="mr-2">About me</span>
            <i class="fas fa-user"></i>
          </v-btn>

          <v-btn
            id="btnProjects"
            href="#projects"
            class="white--text mt-3"
            text
          >
            <span class="mr-2">My projects</span>
            <i class="fas fa-coffee"></i>
          </v-btn>

          <v-btn id="btnContact" href="#contact" class="white--text mt-3" text>
            <span class="mr-2">Contact</span>
            <i class="fas fa-paper-plane"></i>
          </v-btn>
        </v-col>
      </v-row>
    </v-navigation-drawer>

    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    drawer: false,
    msg: "Portfolio",
  }),
};
</script>
<style>
.code {
  color: rgb(0, 255, 209);
}
</style>
