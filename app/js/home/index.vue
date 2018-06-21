<template lang="html">
    <div>
        <home-header/>
        <h-slider/>
        <novice></novice>
    </div>
</template>

<script>
import HomeHeader from "../public/header.vue"
import HSlider from "./HSlider.vue"
import novice from "./novice"
export default {
    components: {
        HomeHeader,
        HSlider,
        novice,
    },
}
</script>

<style lang="scss" module>
</style>
