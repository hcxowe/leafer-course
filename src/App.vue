<template>
  <div class="h-full">
    <div class="h-full" id="leaferContaier"></div>
  </div>
</template>

<script setup>
import { ref, onMounted } from 'vue'
import { Leafer, Rect } from 'leafer-ui'

const leafer = ref(null)
onMounted(() => {
  leafer.value = new Leafer({
    view: 'leaferContaier'
  })
})
</script>

<style scoped>

</style>
