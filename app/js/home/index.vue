<template lang="html">
    <div>
        <home-header/>
        <h-slider/>
        <novice/>
        <borrow/>
        <money/>
        <product/>
    </div>
</template>

<script>
import HomeHeader from "../public/header.vue"
import HSlider from "./HSlider.vue"
import novice from "./novice.vue"
import Borrow from "./Borrow.vue"
import Money from "./Money.vue"
import Product from "./Product.vue"
export default {
    components: {
        HomeHeader,
        HSlider,
        novice,
        Borrow,
        Money,
        Product,
    },
}
</script>

<style lang="scss" module>
</style>
