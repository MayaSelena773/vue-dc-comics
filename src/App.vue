<template>
  <div id="app">
    <PageHeader />
    <MainContent />
      <!--<Footer>-->
  </div>
</template>

<script>
import PageHeader from './components/PageHeader.vue';
import MainContent from './components/MainContent.vue';

export default {
  name: 'App',
  components: {
    PageHeader,
    MainContent
  },
};
</script>

<style lang="scss">
@import './style/common.scss';
</style>
