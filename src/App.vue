<template>
  <v-app>
    <v-app-bar app color="white" prominent elevate-on-scroll>
      <v-container>
        <v-row class="pt-7">
          <v-col cols="6" md="6" lg="6" xl="6">
            <div>
              <v-img
                alt="Roaworks Logo"
                class="mr-2"
                contain
                src="@/assets/logo-roaworks.png"
                transition="scale-transition"
                max-width="200"
              />
            </div>
          </v-col>
          <v-col cols="6" md="6" lg="6" xl="6" class="d-flex justify-end">
            <v-spacer></v-spacer>
            <v-btn
              rounded
              outlined
              large
              color="light-blue accent-4"
              class="mr-5"
              style="border-width: 3px"
            >
              <span class="text-capitalize font-weight-black"
                >Start a Project</span
              >
            </v-btn>
            <v-menu>
              <template v-slot:activator="{ on, attrs }">
                <v-app-bar-nav-icon
                  v-bind="attrs"
                  v-on="on"
                ></v-app-bar-nav-icon>
              </template>
              <v-list>
                <v-list-item link v-for="(item, index) in items" :key="index" :href="item.to">
                  <v-list-item-title>{{ item.title }}</v-list-item-title>
                </v-list-item>
              </v-list>
            </v-menu>
          </v-col>
        </v-row>
      </v-container>
    </v-app-bar>

    <v-main>
      <router-view />
    </v-main>

    <v-footer color="light-blue lighten-5" class="mt-10">
      <v-container>
        <v-row>
          <v-col cols="12" md="6" lg="6" xl="6">
            <v-img max-width="210" src="@/assets/logo-roaworks.png"></v-img>
          </v-col>
          <v-col cols="12" md="6" lg="6" xl="6">
            <v-row class="d-flex align-center">
              <v-col class="d-flex justify-center">
                <h3>© 2021 RoaWorks All rights reserved.</h3>
              </v-col>
              <v-col>
                <v-btn icon large class="mx-1">
                  <v-icon>mdi-github</v-icon>
                </v-btn>
                <v-btn icon large class="mx-1">
                  <v-icon>mdi-instagram</v-icon>
                </v-btn>
                <v-btn icon large class="mx-1">
                  <v-icon>mdi-youtube</v-icon>
                </v-btn>
              </v-col>
            </v-row>
          </v-col>
        </v-row>
      </v-container>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      items: [
        { title: "Our Clients", to: '#our-clients' },
        { title: "Our Services", to: '#our-service' },
        { title: "Our Works", to: '#our-works' },
        { title: "Start A Project", to: '#start-project' },
      ],
    };
  },
};
</script>

<style scoped>
.company-logo {
  width: clamp(100px, 1vw, 200px);
}
</style>
