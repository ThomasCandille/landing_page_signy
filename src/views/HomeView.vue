<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
  <main class="mx-auto max-w-5xl px-6 py-16 md:px-12">
    <h1 class="text-heading text-primary md:text-title">Signy</h1>
    <p class="mt-6 text-lead">Bienvenue sur la page d’accueil.</p>
    <RouterLink
      to="/exemple"
      class="mt-8 inline-flex rounded-2xl bg-ink px-6 py-3 text-button text-cream transition-colors hover:bg-primary focus-visible:outline-2 focus-visible:outline-offset-4 focus-visible:outline-primary"
    >
      Voir l’exemple Tailwind
    </RouterLink>
  </main>
</template>
