<template>
  <div class="part-indicator">
    {{ text }}
  </div>
</template>

<script setup>
defineProps({
  text: {
    type: String,
    required: true
  }
})
</script>

<style scoped>
.part-indicator {
  position: fixed;
  bottom: 10px;
  right: 20px;
  font-size: 0.8rem;
  opacity: 0.7;
  font-weight: 500;
  background-color: rgba(23, 23, 23, 0.6);
  padding: 3px 8px;
  border-radius: 4px;
  color: white;
  z-index: 100;
}
</style> 