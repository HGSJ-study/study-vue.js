<template>
  <h1>4. Conditional Rendering</h1>
  <span v-if="seen">Condition: True!! Now you can see me</span>
</template>

<script>
export default {
  name: 'ConditionalRender',
  data() {
    return {
      seen: true
    }
  }
}
</script>
