
<template>
  <p class="bg-yellow-200 bg-opacity-50 p-1"><strong>Travail :</strong> Utilisez ce que vous avez vu précedement pour obtenir :</p>
  <img src="../assets/capture-test-grid-form.png" alt="" />
  <hr />

  <section class="p-1">
    <form action="#" class="">
      <fieldset class="">
        <legend class="my-1 border-b-2">Identité</legend>
        <label for="nom">Nom</label><input class="rounded-sm border-2" name="nom" id="nom" type="text" /> <label for="prenom">Prénom</label
        ><input class="rounded-sm border-2" name="prenom" id="prenom" type="text" />
      </fieldset>
      <hr class="py-2" />
      <!-- Completez les classes TW ci-dessous... -->
      <fieldset class="">
        <legend class="my-1 border-b-2">Adresse</legend>
        <label for="lignes-adresse">Adresse</label
        ><textarea class="rounded-sm border-2" name="lignes-adresse" id="lignes-adresse" rows="3"></textarea>
        <label for="code-postal">Code postal</label
        ><input class="rounded-sm border-2" name="code-postal" id="code-postal" type="number" min="0" max="99999" />
        <label for="ville">ville</label><input class="rounded-sm border-2" name="ville" id="ville" type="text" />
      </fieldset>
    </form>
  </section>
</template>

<script>
export default {
  components: {},
};
</script>