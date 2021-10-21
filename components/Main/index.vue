<template>
  <div class="Main d-flex flex-column fill-height py-12 px-8">
    <header class="mb-8">
      <v-row>
        <v-col>
          <LoadingCard />
        </v-col>
        <v-col>
          <LoadingCard />
        </v-col>
      </v-row>
    </header>
    <main>
      <v-row fill-height>
        <v-col class="col-lg-9">
          <LoadingCard v-for="i in 3" :key="i" class="mb-8" />
        </v-col>
        <v-col class="col-lg-3 fill-height">
          <LoadingCard v-for="i in 3" :key="i" class="rounded-0" />
        </v-col>
      </v-row>
    </main>
  </div>
</template>