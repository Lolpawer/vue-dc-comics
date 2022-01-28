<template>
  <div id="app">
    <header-box :nav="nav"/>
    <main-box/>
    <footer-box/>
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'
import MainBox from './components/MainBox.vue'
import FooterBox from './components/FooterBox.vue'

export default {
  name: 'App',
  components: {
    HeaderBox,
    MainBox,
    FooterBox
  },
  data() {
    return {
      nav: [
        {
          text: 'CHARACTERS'
          },
        {
          text: 'COMICS'
          },
        {
          text: 'MOVIES'
          },
        {
          text: 'TV'
          },
        {
          text: 'GAMES'
          },
        {
          text: 'COLLECTIBLES'
          },
        {
          text: 'VIDEOS'
          },
        {
          text: 'FANS'
          },
        {
          text: 'NEWS'
          },
        {
          text: 'SHOP'
          },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>
  @import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
  @import './style/main.scss';

</style>
