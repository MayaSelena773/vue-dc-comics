<template>
  <div id="app">
    <PageHeader />
    <MainContent />
    <PageBanner />
      <!--<Footer>-->
  </div>
</template>

<script>
import PageHeader from './components/PageHeader.vue';
import MainContent from './components/MainContent.vue';
import PageBanner from './components/PageBanner.vue';

export default {
  name: 'App',
  components: {
    PageHeader,
    MainContent,
    PageBanner
  },
};
</script>

<style lang="scss">
@import './style/common.scss';
</style>
