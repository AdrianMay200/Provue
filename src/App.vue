<script setup>

import nombre from './components/Cabeza.vue'
import lado from './components/Cuerpo.vue'
</script>

<template>
  <header>
    <nombre />
  </header>

  <main>
    <cabecera />
  </main>
  <aside class="bg-gray-200">
    <lado/>
      
  </aside>
</template>
