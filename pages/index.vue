<template>
  <v-app>
    <v-container fluid class="pa-0">
      <v-app-bar class="d-block d-md-none">
        <img src="@/static/bp.png" style="width: 100%; min-width: 175px; max-width: 230px;" />
      </v-app-bar>
      <v-row no-gutters>
        <v-col md="3" class="d-none d-md-block pa-sm-4 py-md-6 px-md-8" style="min-height: 200px; background: white; z-index: 999;">
          <Nav />
        </v-col>
        <v-col md="9">
          <Main />
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>