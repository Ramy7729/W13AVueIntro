<template>
    <main>
        <div class="gridContainer" >
        <p>
            A Eurogame, also called a German-style board game, German game, or Euro-style game, is a class of tabletop games that generally has indirect player interaction and abstract physical components. Though not all eurogames are European and not all of them are board games, they share a set of similar characteristics. A game need not fit ALL the criteria to be considered a Eurogame. Eurogames are sometimes contrasted with American-style board games, which generally involve more luck, conflict, and drama.[1] They are usually less abstract than chess or Go, but more abstract than wargames. Likewise, they generally require more thought and planning than party games such as Pictionary or Trivial Pursuit.
        </p> 
        <page-image/>
        <side-panel/>
        <meet-the-designers/>
        </div>
    </main>
</template>


<script>
// Importing sub-components to make up the content of the page.
// Each component is a module that is specific to the page.
import PageImage from './PageImage.vue'
import SidePanel from './SidePanel.vue'
import MeetTheDesigners from './MeetTheDesigners.vue'

// Declaring and registering multiple components.
export default {
  name: 'page-body',
  components: {
    PageImage,
    SidePanel,
    MeetTheDesigners
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.gridContainer {
    display: grid;
    grid-template-columns: 1fr;
    max-width: 1000px;
    border: 3px solid #9596B4;
    height: 100vh;
    background-color: 	#f8f8ff;
    
}

p {
    font-size: 1.3em;
    line-height: 1.6em;
    margin-left: 20px;
    margin-right: 20px;
}

</style>
