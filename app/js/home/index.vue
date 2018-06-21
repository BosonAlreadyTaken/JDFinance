<template lang="html">
    <div>
        <home-header/>
        <h-slider/>
        <novice/>
        <borrow/>
    </div>
</template>

<script>
import HomeHeader from "../public/header.vue"
import HSlider from "./HSlider.vue"
import novice from "./novice.vue"
import Borrow from "./Borrow.vue"
export default {
    components: {
        HomeHeader,
        HSlider,
        novice,
        Borrow,
    },
}
</script>

<style lang="scss" module>
</style>
