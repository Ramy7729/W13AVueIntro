<template>
    <div id="sidePanelStyle" >
        <a href="">Home</a>
        <a href="">About</a>
        <a href="">Contact</a>
        <a href="">Location</a>
    </div>
</template>

<script>

// Registering the component which allows it to be imported in other files.
// Will be used as a sub-component for PageBody.vue.
export default {
  name: 'side-panel',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

#sidePanelStyle {
  height: 100%;
  width: 170px;
  background-color:	#53A3A5;
  padding-top: 20px;
  position: fixed;
  z-index: 1;
  top: 0;
  left: 0;
  overflow-x: hidden;
  
}

a {
    font-size: 1.3em;
    display: block;
    text-align: center;
    text-decoration: none;
    padding: 10px;
}
</style>
