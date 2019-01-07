<template>
  <div v-editable="blok"
    :class="blok.style.join(' ')"
  >
    <h1>Test</h1>
    <h2>{{ blok.subtitle }}</h2>
  </div>
</template>

<script>
export default {
  props: ['blok']
}
</script>
