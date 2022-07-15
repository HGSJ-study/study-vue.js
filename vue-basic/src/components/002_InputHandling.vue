<template>
  <h1>2. Input Handling</h1>
  <p>{{ res }}</p>
  <button v-on:click="sum">Answer</button>
</template>

<script>
export default {
  name: 'InputHandling',
  data() {
    return {
      a: 1,
      b: 2,
      res: '1 + 2 = ?'
    }
  },
  methods: {
    sum() {
      this.res = this.a + this.b;
    }
  }
}
</script>
