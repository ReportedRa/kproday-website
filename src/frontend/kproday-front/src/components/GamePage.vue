<script>
import TopGame from './TopGame.vue'
import OptionsGame from './OptionsGame.vue'
import ProductsGame from './ProductsGame.vue'
import SiteHeader from './SiteHeader.vue'
import SiteFooter from './SiteFooter.vue'
import LoginPage from './LoginPage.vue'

export default {
    components: {
        TopGame,
        OptionsGame,
        ProductsGame,
        SiteHeader,
        SiteFooter,
        LoginPage
    },
}
</script>

<template>
    <main>
        <div class="cont-game">
            <site-header></site-header>
            <login-page></login-page>
            <top-game></top-game>
            <options-game></options-game>
            <products-game></products-game>
            <site-footer></site-footer>
        </div>
    </main>
</template>

<style></style>