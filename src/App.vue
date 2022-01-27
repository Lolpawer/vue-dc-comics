<template>
  <div id="app">
    <header-box>
    </header-box>
    <main-box>
    </main-box>
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'
import MainBox from './components/MainBox.vue'

export default {
  name: 'App',
  components: {
    HeaderBox,
    MainBox
  }
}
</script>

<style lang="scss" scoped>
  @import './style/main.scss'

</style>
