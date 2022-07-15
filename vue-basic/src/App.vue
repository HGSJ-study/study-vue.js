<template>
  <DeclarativeRender />
  <InputHandling />
  <TwoWayBinding />
  <ConditionalRender />
</template>

<script>
import DeclarativeRender from './components/001_DeclarativeRender.vue'
import InputHandling from './components/002_InputHandling.vue'
import TwoWayBinding from './components/003_TwoWayBinding.vue'
import ConditionalRender from './components/004_ConditionalRender.vue'

export default {
  name: 'App',
  components: {
    DeclarativeRender,
    InputHandling,
    TwoWayBinding,
    ConditionalRender
  }
}
</script>
