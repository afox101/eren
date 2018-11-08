<template>
  <transition name="router-anim" enter-active-class="animated fadeInDown" leave-active-class= "fadeOutDown" appear>
  <div class="contact page">
    Under Cockstructions
  </div>
</transition>
</template>

<script>
export default {
  name: 'contact',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.contact.page {
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
</style>
