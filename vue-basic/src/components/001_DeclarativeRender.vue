<template>
  <h1>{{ msg }}</h1>
  <h2 v-bind:title="msg2">Title??</h2>
</template>

<script>
export default {
  name: 'DeclarativeRender',
  data() {
    return {
      msg: 'Declarative Rendering!!',
      msg2: 'Title!!'
    }
  }
}
</script>
