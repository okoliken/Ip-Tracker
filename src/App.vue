<script setup>
import IpInputField from './components/IpInputField.vue'
import Results from './components/Results.vue'
</script>

<template>
  <div class="blue-bg">
    <div class="py-8">
      <h2 class="text-center font-semibold text-3xl text-white">IP Address Tracker</h2>
      <IpInputField />
    </div>
    <Results />
  </div>
</template>
