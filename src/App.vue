<script setup>
import UserSection from './components/UserSection.vue'
import CounterSection from './components/CounterSection.vue'
import ComunicationSection from './components/ComunicationSection.vue'
import LifecycleSection from './components/LifecycleSection.vue'

</script>

<template>
  
  <div class="container py-4">
        <h1 class="text-center text-success mb-4">Reactivity in Vue 3</h1>
  </div>
  <counter-section />
  <user-section />
  <ComunicationSection />
  <LifecycleSection />
</template>
