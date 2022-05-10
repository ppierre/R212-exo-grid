
<template>
  <p class="bg-yellow-200 bg-opacity-50 p-1">
    Liser la partie "Design responsive sans media queries" du
    <a href="https://la-cascade.io/css-grid-comment-fonctionne-minmax/">guide sur "minmax"</a>. Pour automatiquement disposer les images en
    une grille d'un nombre variable de colonnes.<br />
    P.S. : <code>grid-auto-flow</code> pour ne pas avoir de trous quand on agrendi un écureuil. <strong>Travail :</strong> Appliquez cela au
    rendu du site d'agence immobiliére (le rendu pour jeudi). Les fiches de maisons doivent se mettre automatiquement sur plusieurs colonnes
    (comme les écureuils).
  </p>
  <hr />

  <section class="p-1">
    <div class="grid grid-flow-row-dense grid-cols-[repeat(auto-fit,minmax(100px,1fr))]">
      <!-- Ajoutez ci-dessus les classes TW pour mettre en grille avec un nombre variable de colonnes -->
      <img
        v-for="n in 17"
        :key="n"
        :src="`/img-squirrel/squirrel-${n}.jpg`"
        alt="Squirrel"
        class="w-full"
        @click="active = n"
        :class="{ 'col-span-full border-4 border-red-500': n === active }"
      />
      <!-- Ajoutez une classe TW pour que l'élément actif couvre toutes les colonnes -->
    </div>
  </section>
</template>

<script>
export default {
  data: () => ({
    active: 8,
  }),
  components: {},
};
</script>