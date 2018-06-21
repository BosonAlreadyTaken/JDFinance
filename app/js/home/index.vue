<template lang="html">
    <div>
        <home-header/>
        <h-slider/>
        <novice/>
        <borrow/>
        <money/>
    </div>
</template>

<script>
import HomeHeader from "../public/header.vue"
import HSlider from "./HSlider.vue"
import novice from "./novice.vue"
import Borrow from "./Borrow.vue"
import Money from "./Money.vue"
export default {
    components: {
        HomeHeader,
        HSlider,
        novice,
        Borrow,
        Money,
    },
}
</script>

<style lang="scss" module>
</style>
