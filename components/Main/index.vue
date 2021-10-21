<template>
  <div class="Main d-flex flex-column fill-height py-12 px-8">
    <header class="mb-8">
      <v-row>
        <v-col md="6">
          <LoadingCard />
        </v-col>
        <v-col md="6">
          <LoadingCard />
        </v-col>
      </v-row>
    </header>
    <main>
      <v-row fill-height>
        <v-col md="9">
          <LoadingCard v-for="i in 3" :key="i" class="mb-8" />
        </v-col>
        <v-col md="3" class="d-none d-md-block fill-height">
          <LoadingCard v-for="i in 4" :key="i" class="rounded-0" />
        </v-col>
      </v-row>
    </main>
  </div>
</template>