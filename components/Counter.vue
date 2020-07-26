<template>
  <div class="mx-auto shadow-lg p-5">
    <div class="text-gray-900">{{ counter }}</div>
    <button @click="increment" class="border rounded text-gray-800">
      Increment
    </button>
  </div>
</template>
<script>
import { ref } from 'nuxt-composition-api'
export default {
  setup() {
    const counter = ref(0)
    const increment = () => {
      counter.value++
    }
    return {
      counter,
      increment,
    }
  },
}
</script>
