<template>
  <div id="app">
    <PageHeader />
    <main>
       <MainContent />
       <MainList />

    </main>
    
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import PageHeader from './components/PageHeader.vue'
import MainContent from './components/MainContent.vue'
import MainList from './components/MainList.vue'

export default {
  name: 'App',
  components: {
    PageHeader,
    MainContent,
    MainList,
    
  }
}
</script>

<style lang="scss">
@import './style/common';

</style>
