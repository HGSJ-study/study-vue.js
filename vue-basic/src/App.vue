<template>
  <DeclarativeRender />
  <InputHandling />
  <TwoWayBinding />
</template>

<script>
import DeclarativeRender from './components/001_DeclarativeRender.vue'
import InputHandling from './components/002_InputHandling.vue'
import TwoWayBinding from './components/003_TwoWayBinding.vue'

export default {
  name: 'App',
  components: {
    DeclarativeRender,
    InputHandling,
    TwoWayBinding
  }
}
</script>
