<template>
  <h1>3. Two Way Binding</h1>
  <p>{{ message }}</p>
  <input type="text" v-model="message" />
</template>

<script>
export default {
  name: 'TwoWayBinding',
  data() {
    return {
      message: 'Hello?'
    }
  }
}
</script>
