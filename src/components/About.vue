<template>
  <transition name="router-anim" enter-active-class="animated fadeInDown" leave-active-class= "fadeOutDown" appear>
  <div class="about page">
    <div class="summary">
    <p>Eren Cannata's natural talent and genuine artistry has made him one of the most promising up and coming artists today. Bringing universal appeal to his music and performances, he will undoubtedly sustain widespread success in the industry for decades to come.
<br><br>
Growing up in a musical household, his talent has been evident from a young age. His first recording session at the age of two was only the precursor to his future in the music industry. Soon after he acted in a movie "Under the Cover of Darkness" with Richard Bradford and for several years he was on the award winning "As the World Turns". These experiences prompted him to learn all components of the business, from the technical to the artistic. At this young age, he also began his musical journey with piano and guitar lessons, and continued to study and evolve.</p>
</div>
<img class="erenface" src="../assets/erenface.png">
  </div>
</transition>
</template>

<script>
export default {
  name: 'about',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.about {
  display: flex;
  position: relative;
  flex-grow: 1;
  flex-direction: column;
  justify-content: space-between;
  animation-duration: 3.5s;
}

.summary {
  margin: 10px 50px 0px 50px;
}

.erenface {
  transition: 3s;
}

.erenface:hover {
  filter: hue-rotate(180deg);
}
p {
  color: white;
}
img {
  position: fixed;
  margin-top: 350px;
  align-self: center;
}
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
