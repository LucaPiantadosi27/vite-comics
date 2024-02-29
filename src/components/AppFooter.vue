<script>
import AppFooterTop from './FooterTop.vue';
import AppFooterBottom from './FooterBottom.vue';
export default {
    name: 'AppFooter',
    components: {
        AppFooterTop,
        AppFooterBottom
    }
}
</script>

<template>
    <footer>
        <AppFooterTop></AppFooterTop>
        <AppFooterBottom></AppFooterBottom>
    </footer>
</template>

<style scoped></style>