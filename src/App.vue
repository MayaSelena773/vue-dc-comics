<template>
  <div id="app">
    <PageHeader />
    <MainContent />
    <PageBanner />
    <PageFooter />
  </div>
</template>

<script>
import PageHeader from './components/PageHeader.vue';
import MainContent from './components/MainContent.vue';
import PageBanner from './components/PageBanner.vue';
import PageFooter from './components/PageFooter.vue';

export default {
  name: 'App',
  components: {
    PageHeader,
    MainContent,
    PageBanner,
    PageFooter
  },
};
</script>

<style lang="scss">
@import './style/common.scss';
</style>
