<template>
    <div id="teamGrid" >
        <h1>Meet The Designers</h1>
        <div class="teamCard" >
            <img src="../assets/vitalLacerda.jpg" alt="Vital Lacerda">
            <p>
               Born in Lisbon, Vital Lacerda has a masters degree in Marketing and Advertising. After working in advertising agencies for almost 15 years as an art director, and later as the creative director of his own agency, he decided to try his luck as a freelance graphic designer in 2006. Boardgame design is his greatest and most loved passion.
            </p>
        </div>
        <div class="teamCard" >
            <img src="../assets/stefanFeld.jpg" alt="Stefan Feld">
            <p>
                Stefan Feld (born 1970 in Karlsruhe, Germany) is a German-style board game designer who lives in Gengenbach, Baden-Württemberg, Germany.Feld is considered one of the most prominent designers of the Eurogame genre. He is particularly known for the ingenious use of dice in his games, using them to add variety and different options without excessive randomness. Three of the games he has designed, Strasbourg, Bruges, and Carpe Diem have been nominated for the prestigious award Kennerspiel des Jahres in Germany. Many of his games feature artwork from game artist Harald Lieske.
            </p>
        </div>
        <div class="teamCard" >
            <img src="../assets/shemPhillips.jpg" alt="Shem Philips">
            <p>
               Shem Phillips founded Garphill Games in 2009 and has published a wide range of games since. He is most well known for his designs in the North Sea and West Kingdom Trilogies.
            </p>
        </div>
    </div>
</template>

<script>

// Registering component for use in other vue files.
// Will be used as a sub-component for PageBody.vue.
export default {
  name: 'meet-the-designers'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#teamGrid {
    display: grid;
    grid-template-columns: 1fr;
    grid-auto-rows: auto;
    place-items: center;
    line-height: 1.6em;
    row-gap: 2em;
    margin-top: 3em;
}

.teamCard {
    display: grid;
    grid-template-columns: 1fr 1fr;
    align-items: center;
    border: 3px #9596B4 solid;
    background-color: 	#f8f8ff;
}

p {
    font-size: 1.2em;
    margin-right: 3em;
}

img {
    height: 400px;
    width: 400px;
}

</style>
