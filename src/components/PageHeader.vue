<template>
  <header>
      <h1>{{title}}</h1>
  </header>
</template>

<script>

// Registering the component which allows it to be imported in other files.
export default {
  name: 'page-header',
  props: {
    title: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
    font-size: 2.7em;
}


</style>
