<template>
  <div class="Nav d-flex flex-column fill-height py-6 px-10">
    <div class="flex-grow-1">
      <header>
        <img src="@/static/bp.png" style="max-width: 100%;" />
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