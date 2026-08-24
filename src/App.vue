<template>
  <v-app>
    <v-main>
      <div class="under-construction">
        <img
          src="/under_construction0.png"
          alt="Страница в разработке"
          class="under-construction__image"
        />
      </div>
    </v-main>
  </v-app>
</template>

<script lang="ts">
export default {
  name: 'App',
};
</script>

<style scoped lang="sass">
.under-construction
  display: flex
  align-items: center
  justify-content: center
  min-height: 100vh
  width: 100%

.under-construction__image
  max-width: 100%
  height: auto
</style>
