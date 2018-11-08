 <template>
  <div id="app">
    <div class="pic">
  </div>
    <div id="nav">
      <router-link to="/">HOME /  </router-link>
      <router-link to="/about"> ABOUT / </router-link>
      <router-link to="/discography"> CLIENTS / </router-link>
      <router-link to="/contact"> CONTACT</router-link>
    </div>
    <img class="stache" src="./assets/erenstache.png">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
};
</script>

<style>

@import "https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.0/animate.min.css";
@import url('https://fonts.googleapis.com/css?family=PT+Sans');


a {
  font-size: 30px;
  font-family: "PT Sans";
  font-weight: bold;
  color: white;
  font-style: normal;
  text-decoration: none;
}

body {
  background-image: url("./assets/gradient1.jpg");
}

.pic {

  animation: scale 2s ease-in-out forwards;
  animation-duration: 6s;

}

.stache {
  margin-top: 30px;
  width: 275px;
  height: 100px;
  transform: rotate(90deg);
  transition: 2s;
  animation: rotate 2s ease-in-out forwards;
  animation-delay: 3s;
}

@keyframes rotate {
  from { transform: rotate(90deg) }
  to { transform: rotate(0deg); }
}

@keyframes scale {
  from { transform: translateY(300px); }
  to { transform: translateY(0px); }
}

.stache:hover {
  filter: saturate(5);
  transition: 2s;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.page {
  position: relative;
  width: inherit;
}

</style>
