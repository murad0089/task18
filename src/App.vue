<template>
  <div id="app">
    <Header></Header>
    <Hero></Hero>
    <HereIsWhatYouGet></HereIsWhatYouGet>
    <AboutFork></AboutFork>
    <Subscription></Subscription>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Hero from './components/Hero.vue';
import HereIsWhatYouGet from './components/HereIsWhatYouGet.vue';
import AboutFork from './components/AboutFork.vue';
import Subscription from './components/Subscription.vue';

export default {
  name: 'App',
  components: {
    Header,
    Hero,
    HereIsWhatYouGet,
    AboutFork,
    Subscription
}
}
</script>

<style>

</style>
