<template>

    <header>
        <MyHeaderTop></MyHeaderTop>
        <MyJumbotrone></MyJumbotrone>
    </header>
  
</template>

<script>

import MyHeaderTop from './partials/MyHeaderTop.vue'
import MyJumbotrone from './partials/MyJumbotrone.vue'

export default {
    name: 'MyHeader',
    components:{
        MyHeaderTop,
        MyJumbotrone,
    }
}
</script>

<style lang="scss">
    

    
</style>