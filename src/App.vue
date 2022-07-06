<template>
  <div id="app">
    <PageHeader />
    <main>
       <MainContent />
    </main>
    
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import PageHeader from './components/PageHeader.vue'
import MainContent from './components/MainContent.vue'

export default {
  name: 'App',
  components: {
    PageHeader,
    MainContent,
    
  }
}
</script>

<style lang="scss">
@import './style/common';

</style>
