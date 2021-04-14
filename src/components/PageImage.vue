<template>
    <div>
        <img src="../assets/cob.jpg" alt="">
        <img src="../assets/concordia.jpg" alt="">
        <img src="../assets/kanbanev.jpg" alt="">
        <img src="../assets/raiders.jpg" alt="">
        <img src="../assets/thegallerist.png" alt="">
        <img src="../assets/viticulture.jpg" alt="">
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
