<template>
  <h1>1. Declarative Rendering</h1>
  <h2>{{ msg }}</h2>
  <h2 v-bind:title="msg2">Title??</h2>
</template>

<script>
export default {
  name: 'DeclarativeRender',
  data() {
    return {
      msg: 'Rendering!!',
      msg2: 'Title!!'
    }
  }
}
</script>
