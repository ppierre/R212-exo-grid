<template>
  <p class="bg-yellow-200 bg-opacity-50 p-1">
    <strong>Travail :</strong> Utilisez
    <a class="text-blue-700" href="https://tailwindcss.com/docs/display#grid"><code class="font-mono">grid</code></a>
    et
    <a class="text-blue-700" href="https://tailwindcss.com/docs/place-content"><code class="font-mono">place-content-xxx</code></a> pour
    centrer le titre et le sous-titre en hauteur et largeur.
  </p>
  <hr />

  <section class="h-[calc(60vw/320*240)] w-[60vw] bg-[url('https://loremflickr.com/320/240/cat&lock=11')] bg-cover">
    <!-- Deux classe TW à ajouter ci-dessus... -->
    <div class="bg-gray-500 bg-opacity-50">
      <h1 class="text-2xl">Titre</h1>
      <p>Sous-titre</p>
    </div>
  </section>
</template>

<script>
export default {
  components: {},
};
</script>