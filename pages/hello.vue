<template>
  <div class="container mx-auto bg-blue-300 min-h-screen">
    <div class="text-2xl">Hello World!</div>
    <counter />
  </div>
</template>
<script>
import Counter from '@/components/Counter'
export default {
  components: {
    Counter,
  },
}
</script>
