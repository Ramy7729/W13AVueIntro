<template>
  <footer>
    <p>Hello I'm a fixed footer.</p>
  </footer>
</template>

<script>
// Registering the component which allows it to be imported in other files.
export default {
  name: 'page-footer',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

footer {
  
  background-color: #fffafa;
  position: fixed;
  bottom: 0;
  width: 100%;
  border: 3px solid #9596B4;
}

p {
  font-size: 1.3em;
  text-align: center;
  
}
</style>
