<template>

    <main>
        <SectionVideo></SectionVideo>
        <SectionDoing></SectionDoing>
        <SectionBusiness></SectionBusiness>
        <SectionTeam></SectionTeam>
        <SectionNews></SectionNews>
        <SectionNewsletter></SectionNewsletter>
        <SectionMessage></SectionMessage>  
    </main>
    
</template>

<script>

import SectionVideo from './partials/SectionVideo.vue'
import SectionDoing from './partials/SectionDoing.vue'
import SectionBusiness from './partials/SectionBusiness.vue'
import SectionTeam from './partials/SectionTeam.vue'
import SectionNews from './partials/SectionNews.vue'
import SectionNewsletter from './partials/SectionNewsletter.vue'
import SectionMessage from './partials/SectionMessage.vue'

export default {
    name: 'MyMain',
    components: {
        SectionVideo,
        SectionDoing,
        SectionBusiness,
        SectionTeam,
        SectionNews,
        SectionNewsletter,
        SectionMessage,
    }
}
</script>

<style lang="scss">
    


    

    
</style>