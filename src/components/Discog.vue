<template>
  <transition name="router-anim" enter-active-class="animated fadeInDown" leave-active-class= "fadeOutDown" appear>
  <div class="discog page">
    <div class="card-deck">
      <a href="http://codysimpson.com/">
  <div class="card">
    <img class="card-img-top" src="../assets/cody.jpg" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">CODY SIMPSON</h5>
    </div>
  </div>
</a>
<a href="http://www.donnymccaslin.com/">
  <div class="card">
    <img class="card-img-top-donny" src="../assets/donny.jpg" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">DONNY MCCASLIN</h5>
    </div>
  </div>
</a>
  <a href="https://en.wikipedia.org/wiki/Brie_Larson">
  <div class="card">
    <img class="card-img-top" src="../assets/brie.jpg" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">BRIE LARSON</h5>
    </div>
  </div>
</a>
  <a href="http://www.chefspecialmusic.com/">
    <div class="card">
    <img class="card-img-top" src="../assets/chefs.jpg" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">CHEF'SPECIAL</h5>
    </div>
  </div>
</a>
<a href="http://dreamtheater.net/">
   <div class="card">
    <img class="card-img-top" src="../assets/dream.jpg" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">DREAMTHEATER</h5>
    </div>
  </div>
</a>
<a href="https://pasta.com/">
<div class="card">
    <img class="card-img-top" src="../assets/lasagna.jpg" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">Fresh Lasagna</h5>
    </div>
  </div>
</a>
</div>
  </div>
</transition>
</template>

<script>
export default {
  name: 'discog',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

a {
  color: white;
}

@import "https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css"



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

img {
  padding-top: 2rem;
  width: auto;
  height: 10rem;
}
.card {
  border: solid;
  width: 20rem;
  font-size: 35px;
}

.card:hover {
  cursor: pointer;
  filter: contrast(5);

}
.card-deck {
  padding-top: 50px;
  width: 100%;
  display: flex;
  position: relative;
  flex-wrap: wrap;
  justify-content: space-around;
  overflow-y: auto;
}
.card-img-top-donny {

}

</style>
