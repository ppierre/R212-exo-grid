<template>
  <nav>
    <ul>
      <li>
        exo 1 : <router-link class="text-red-600 underline" to="/exo-1-1"> partie 1</router-link>,
        <router-link class="text-red-600 underline" to="/exo-1-2"> partie 2</router-link>,
        <router-link class="text-red-600 underline" to="/exo-1-3"> partie 3</router-link>,
        <router-link class="text-red-600 underline" to="/exo-1-4"> partie 4</router-link>
      </li>
      <li><router-link class="text-red-600 underline" to="/exo-2">exo 2 (centrage)</router-link></li>
      <li><router-link class="text-red-600 underline" to="/exo-3">exo 3 (formulaire)</router-link></li>
      <li><router-link class="text-red-600 underline" to="/exo-4">exo 4 (écureuil)</router-link></li>
    </ul>
  </nav>

  <!-- Affiche les pages -->
  <router-view class="m-2 border-2 p-2" />
</template>

<script>
import { MenuIcon } from "@heroicons/vue/solid";

export default {
  name: "App",
  components: { MenuIcon },
};
</script>
