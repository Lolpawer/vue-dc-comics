<template>
    <div>
        <footer-top></footer-top>
        <footer-middle></footer-middle>
        <footer-bottom></footer-bottom>
   </div>
</template>

<script>
import FooterTop from './FooterTop.vue'
import FooterMiddle from './FooterMiddle.vue'
import FooterBottom from './FooterBottom.vue'

export default {
    components: {
        FooterTop,
        FooterMiddle,
        FooterBottom
    }
}

</script>

<style lang="scss" scoped>
</style>