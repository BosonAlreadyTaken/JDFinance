<template lang="html">
    <div>
        <home-header/>
        <h-slider/>
        <novice/>
        <borrow/>
        <money/>
        <product/>
        <life/>
        <home-footer/>
        <navbar/>
    </div>
</template>

<script>
import HomeHeader from "../public/header.vue"
import HomeFooter from "../public/footer.vue"
import Navbar from "../public/Navbar.vue"
import HSlider from "./HSlider.vue"
import novice from "./novice.vue"
import Borrow from "./Borrow.vue"
import Money from "./Money.vue"
import Product from "./Product.vue"
import Life from "./life.vue"
export default {
    components: {
        HomeHeader,
        HomeFooter,
        Navbar,
        HSlider,
        novice,
        Borrow,
        Money,
        Product,
        Life,
    },
}
</script>

<style lang="scss" module>
</style>
