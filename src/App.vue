<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import AppJumbo from './components/AppJumbo.vue';
import AppComics from './components/AppComics.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    AppMain,
    AppFooter,
    AppJumbo,
    AppComics
  }
}
</script>

<template>
  <AppHeader></AppHeader>
  <AppJumbo></AppJumbo>
  <AppComics></AppComics>
  <AppMain></AppMain>
  <AppFooter></AppFooter>
</template>

<style scoped></style>