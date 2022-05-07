<template>
  <p class="bg-yellow-200 bg-opacity-50 p-1">
    <strong>Travail :</strong> Utilisez
    <a class="text-blue-700" href="https://tailwindcss.com/docs/grid-template-columns#arbitrary-values">
      <code class="font-mono">grid-cols-[valeurs_arbitraires]</code>
    </a>
    ou un style intégré <code class="font-mono">style="grid-template-columns: valeurs arbitraires"</code> avec
    <a class="text-blue-700" href="https://la-cascade.io/css-grid-comment-fonctionne-minmax">
      <code class="font-mono">minmax(___,___)</code>
    </a>
    pour obtenir 3 colonnes comme décrites dans les textes.
  </p>

  <hr />

  <section class="">
    <!-- complétez ci-dessus... -->
    <header class="bg-rose-400">
      <h1 id="logo" class="bg-rose-200 text-2xl"><a href="#logo">LOGO</a></h1>
      <nav>
        <h3 class="text-xl">Menu principal</h3>
        <ul>
          <li><a href="#1">Lien du menu 1</a></li>
          <li><a href="#2">Lien du menu 2</a></li>
          <li><a href="#3">Lien du menu 3</a></li>
          <li><a href="#4">Lien du menu 4</a></li>
          <li><a href="#5">Lien du menu 5</a></li>
        </ul>
        <p>Doit faire une taille normale</p>
        <p>Celle de son contenu.</p>
        <p>Pas plus, pas moins</p>
      </nav>
    </header>
    <main class="bg-cyan-300">
      <h1 class="text-2xl">Contenu</h1>
      <p>Doit occuper le plus de place possible et jamais moins de 15rem en largeur</p>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusamus ad, alias aliquid beatae blanditiis consequatur culpa cumque
        deleniti dolores, eius est et ex exercitationem expedita hic id in iste itaque labore minima molestiae natus odio optio porro quae,
        quam quasi quisquam recusandae reiciendis repellat rerum sed sint suscipit tempore vero voluptate voluptatum! Adipisci cupiditate
        dolorem possimus saepe veritatis. Architecto, et.
      </p>
    </main>
    <aside class="bg-amber-100">
      <p>Doit faire 10rem de largeur peut réduire si nécessaire</p>
    </aside>
  </section>
</template>

<script>
export default {
  components: {},
};
</script>