<template>
  <div id="app">
    <page-header title="Euro Style Board Games"/>
    <page-body/>
    <page-footer/>
  </div>
</template>

<script>

// Importing components to make up the content of the page.
// Each component is a module that is specific to the page.
import PageHeader from './components/PageHeader.vue'
import PageBody from './components/PageBody.vue'
import PageFooter from './components/PageFooter.vue'

// Registering components for use in other vue files.
export default {
  name: 'App',
  components: {
    PageHeader,
    PageBody,
    PageFooter
  }
}
</script>

<style>

body {
  background-color: #fffafa;
}
  
#app {
  display: grid;
  place-items: center;
}
</style>
