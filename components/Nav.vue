<template>
  <div class="Nav d-flex flex-column fill-height" style="position: fixed;">
    <div class="flex-grow-1">
      <header class="white">
        <img src="@/static/bp.png" style="width: 100%; min-width: 175px; max-width: 230px;" />
      </header>
      <div class="mb-12" style="max-width: 250px;">
        <LoadingLine v-for="i in 6" :key="i" class="my-3" />
      </div>
      <div style="max-width: 135px;">
        <LoadingLine v-for="i in 5" :key="i" class="my-3" />
      </div>
    </div>
    <LoadingAvatar />
  </div>
</template>