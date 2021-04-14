<template>
    <div>
        <img src="../assets/cob.jpg" alt="The Castles of Burgundy board game">
        <img src="../assets/concordia.jpg" alt="Concordia board game">
        <img src="../assets/kanbanev.jpg" alt="Kanban EV board game">
        <img src="../assets/raiders.jpg" alt="Raiders of the North Sea board game">
        <img src="../assets/thegallerist.png" alt="The Gallerist board game">
        <img src="../assets/viticulture.jpg" alt="Viticulture board game">
    </div>
</template>

<script>

// Registering the component which allows it to be imported in other files.
// Will be used as a sub-component for PageBody.vue.
export default {
  name: 'page-image',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
div {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    place-items: center;
    margin-bottom: 4em;
    row-gap: 2em;

}

img {
    height: 300px;
    width: 300px;
}

</style>
