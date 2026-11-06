<template>
  <main class="min-h-screen bg-cream px-6 py-12 font-sans text-ink md:px-12 md:py-20">
    <div class="mx-auto max-w-5xl space-y-10">
      <!-- Couleurs du thème, typographie et tailles adaptées à l'écran. -->
      <section class="rounded-3xl bg-primary p-8 text-cream md:p-12">
        <p class="text-caption font-bold uppercase tracking-widest">Bienvenue chez Signy</p>
        <h1 class="mt-4 text-heading md:text-title">La LSF commence par un signe.</h1>
        <p class="mt-6 max-w-2xl text-body md:text-lead">
          Découvre une nouvelle façon de communiquer, à ton rythme.
        </p>
        <a
          href="#palette"
          class="mt-8 inline-flex rounded-2xl bg-ink px-6 py-3 text-button text-cream transition-colors hover:bg-cream hover:text-ink focus-visible:outline-2 focus-visible:outline-offset-4 focus-visible:outline-cream"
        >
          Découvrir
        </a>
      </section>

      <!-- Grille responsive et couleurs personnalisées. -->
      <section id="palette" aria-labelledby="palette-title" class="scroll-mt-8">
        <h2 id="palette-title" class="text-heading">Les couleurs de Signy</h2>
        <div class="mt-6 grid grid-cols-2 gap-4 md:grid-cols-4">
          <div class="rounded-2xl bg-primary p-6 text-body font-bold text-cream">Violet</div>
          <div class="rounded-2xl bg-lavender p-6 text-body font-bold">Lavande</div>
          <div class="rounded-2xl bg-pink p-6 text-body font-bold">Rose vif</div>
          <div class="rounded-2xl bg-blush p-6 text-body font-bold">Rose tendre</div>
          <div class="rounded-2xl border border-ink/20 bg-cream p-6 text-body font-bold">Crème</div>
          <div class="rounded-2xl bg-ink p-6 text-body font-bold text-cream">Encre</div>
          <div class="rounded-2xl bg-sunshine p-6 text-body font-bold">Soleil</div>
          <div class="rounded-2xl bg-turquoise p-6 text-body font-bold">Turquoise</div>
        </div>
      </section>

      <!-- Échelle typographique et graisses disponibles. -->
      <section aria-labelledby="typography-title" class="rounded-3xl bg-lavender p-8 md:p-12">
        <h2 id="typography-title" class="text-heading">La typographie</h2>
        <div class="mt-6 space-y-4">
          <p class="text-display" aria-hidden="true">Aa</p>
          <p class="text-title">Un grand titre</p>
          <p class="text-heading">Un titre de section</p>
          <p class="text-lead">Une phrase d’introduction.</p>
          <p class="text-body">Un texte courant, facile à lire.</p>
          <p class="text-caption">Une légende pour accompagner le contenu.</p>
        </div>
        <div class="mt-8 flex flex-wrap gap-x-8 gap-y-3 text-body">
          <span class="font-normal">Normal · 400</span>
          <span class="font-medium">Medium · 500</span>
          <span class="font-bold">Bold · 700</span>
          <span class="font-black">Black · 900</span>
        </div>
      </section>
    </div>
  </main>
</template>

