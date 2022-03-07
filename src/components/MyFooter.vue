<template>
    <footer>
        <MyFooterTop></MyFooterTop>
        <MyFooterBot></MyFooterBot>
    </footer>
</template>

<script>

import MyFooterTop from './partials/MyFooterTop.vue'
import MyFooterBot from './partials/MyFooterBot.vue'

export default {
    name: 'MyFooter',
    components:{
        MyFooterTop,
        MyFooterBot
    }
}
</script>

<style lang="scss">
    

    
</style>