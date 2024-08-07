<template>
  <v-footer height="40" app>
    <div
      class="text-caption text-center w-100"
    >
      &copy; {{ (new Date()).getFullYear() }} <span class="d-none d-sm-inline-block">思创一体</span>
      —
      <a
        class="text-decoration-none on-surface"
        href="https://vuetifyjs.com/about/licensing/"
        rel="noopener noreferrer"
        target="_blank"
      >
      桂ICP2024038778号
      </a>
    </div>
  </v-footer>
</template>

<script setup lang="ts">

</script>

<style scoped lang="sass">
  .social-link :deep(.v-icon)
    color: rgba(var(--v-theme-on-background), var(--v-disabled-opacity))
    text-decoration: none
    transition: .2s ease-in-out

    &:hover
      color: rgba(25, 118, 210, 1)
</style>
