<template>
  <v-app>
    <Header class="layout__header" />
    <Nuxt class="layout__main" />
    <Footer class="layout__footer" />
  </v-app>
</template>

<style lang="scss">
.layout {
  &__header {
    min-height: 20vh;
    font-size: 0.5rem;
  }

  &__main {
    width: 100%;
    min-height: 75vh;
  }

  &__footer {
    min-height: 5vh;
  }
}
</style>
