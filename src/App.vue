<template>
  <v-app id="inspire">
    <v-navigation-drawer
      v-model="drawer"
      app
      right
      class="white"
    >
      <!-- Nav menu punkter -->
      
      <li class="menu-item black--text"><a class="black--text" href="#home">Hjem</a></li>
      <li class="menu-item"><a class="black--text" href="#about">Om mig</a></li>
      <li class="menu-item"><a class="black--text" href="#pictures">Portfolio</a></li>
      <li class="menu-item"><a class="black--text" href="#photos">Fotografi</a></li>
      <li class="menu-item"><a class="black--text" href="#kontakt">Kontakt</a></li>

      <!-- <router-link tag="li" to="/">Hjem </router-link>
      <router-link tag="li" class="menu-item black--text" to="/portfolio">Om mig </router-link>
      <router-link tag="li" class="menu-item black--text" to="/portfolio">Portfolie </router-link>
      <router-link tag="li" class= "menu-item black--text" to="/portfolio">Fotografi </router-link>
      <router-link tag="li" class= "menu-item black--text" to="/portfolio">Kontakt </router-link>  -->
    </v-navigation-drawer>

    <v-app-bar app>
    

      <v-toolbar-title>
        <a href="#home">
          <v-img 
          height="55" contain="true" width="58"
            src="./assets/LS final logo5.png"
            > 

          </v-img>
        </a>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>
    </v-app-bar>

    <v-main>
      <Hero />
      <router-view></router-view>
    </v-main>
  </v-app>
</template>


<script>
// @ is an alias to /src

import Hero from "@/components/Hero.vue";

export default {

  components: {
    Hero
  },
  data: () => ({ 
      drawer: null 
    }),
}
</script>


<style lang="scss">
.menu-item:hover {
  background-color: #F5EFEF
}

#app {
  background-image: url('./assets/sunset fili photo.jpg');
  background-size: cover;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffff;
}

.v-navigation-drawer {

  li {
    text-decoration: none;
    list-style-type: none;
    padding: 20px 10px;
    text-align: center;
  }

  padding: 50px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}

</style>
