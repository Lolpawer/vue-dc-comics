<template>
  <div id="app">
    <header-box>
    </header-box>
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'

export default {
  name: 'App',
  components: {
    HeaderBox
  }
}
</script>

<style lang="scss" scoped>
@import './style/main.scss'
</style>
