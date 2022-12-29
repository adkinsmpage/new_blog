<script setup lang="ts">
useHead({
  meta: [
    { property: 'og:title', content: 'Adkimsm' },
    { property: 'og:image', content: 'https://antfu.me/og-icon.png' },
    { name: 'description', content: 'Adkimsm\'s Portfolio' },
    { name: 'twitter:card', content: 'summary' },
    { name: 'twitter:creator', content: '@adkimsm' },
  ],
})
</script>

<template>
  <NavBar />
  <main class="px-7 py-10">
    <router-view />
    <Footer />
  </main>
</template>
