<template>
  <h1>5. List Rendering</h1>
  <ul>
    <li v-for="fruit in fruits" :key="fruit">
      {{ fruit }}
    </li>
  </ul>
</template>

<script>
export default {
  name: 'ListRender',
  data() {
    return {
      fruits: [
        'Apple',
        'Banana',
        'Cherry'
      ]
    }
  }
}
</script>
