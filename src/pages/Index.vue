<template>
  <q-page class="flex flex-center">
    <img
      alt="Quasar logo"
      src="~assets/quasar-logo-full.svg"
    >
  </q-page>
</template>

<script>
export default {
  name: 'PageIndex',
  meta: {
    title: 'title',
    meta: {
      description: {
        name: 'description',
        content: 'description'
      },
      og1: {
        name: 'og:title',
        content: 'og title'
      },
      og2: {
        name: 'og:description',
        content: 'og description'
      }
    }
  }
}
</script>
