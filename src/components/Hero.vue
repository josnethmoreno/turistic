<script lang="ts">
import Button from './Button.vue';

export default {
  name: "Hero",
  components: {
    Button
  }
}
</script>

<template>
  <div class="hero">
    <h1>El futuro de la IA es en <br> nuestro idioma</h1>
    <p class="lead"><b>Suscribete</b> y no te pierdas todo lo que se viene del lanzamiento de <br> nuestra versión beta. Muy pronto!</p>
    <Button></Button>
  </div>
</template>

<style scoped>
  .hero {
    display: flex;
    flex-direction: column;
    text-align: center;
    gap: 1.6rem;
  }
</style>