<template>
  <div id="app">
    <PageHeader />
    <main>
       <JumbotronBanner />
       <MainContent />
       <MainList />

    </main>

    <PageFooter />
    
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import PageHeader from './components/PageHeader.vue'
import MainContent from './components/MainContent.vue'
import MainList from './components/MainList.vue'
import PageFooter from './components/PageFooter.vue'
import JumbotronBanner from './components/JumbotronBanner.vue'

export default {
  name: 'App',
  components: {
    PageHeader,
    MainContent,
    MainList,
    PageFooter,
    JumbotronBanner,
    
  }
}
</script>

<style lang="scss">
@import './style/common';

</style>
