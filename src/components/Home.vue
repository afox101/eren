<template>
  <transition name="router-anim" enter-active-class="animated fadeInDown" leave-active-class= "fadeOutDown" appear>
  <div class="home page">
    <img class="stachetitle" src="../assets/erentitlewhite.png">
 <iframe src="https://open.spotify.com/embed/user/ecsharp/playlist/1TpraxDpYOS6Wq0uozpatm" width="300" height="380" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>
  </div>
</transition>
</template>

<script>
export default {
  name: 'home',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


.home.page {
  display: flex;
  position: relative;
  justify-content: space-around;
}

@keyframes fade {
  from { opacity: 0 }
  to { opacity: 1 }
}

.stachetitle {
  margin-top: 30px;
  animation: fade 10s ease-in-out forwards;
  color: white;
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

.home {
  position: fixed;
  animation-duration: 5s;
}
</style>
