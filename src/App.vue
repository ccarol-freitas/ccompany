<template>
  <div id="app">
    <div class="nav has-shadow">
      <div class="container">
        <div class="nav-left">
          <a href="/" class="nav-item" style="color: #ffffff; font-weigt: 700; font-size: 57">CCompany</a>
        </div>

        <span class="nav-toggle" v-on:click="toggleNav" v-bind:class="{ 'is-active': isActive}">
          <span></span>
          <span></span>
          <span></span>
        </span>

        <div class="nav-right nav-menu"  v-on:click="toggleNav" v-bind:class="{ 'is-active': isActive}">

          <router-link to="/" class="nav-item r-item">Home</router-link>
          <router-link to="features" class="nav-item r-item">Features</router-link>
          <router-link to="about" class="nav-item r-item">About</router-link>
          <router-link to="faq" class="nav-item r-item">FAQ</router-link>

          <div class="nav-item">
            <p class="control">
              <a class="button-join button">
                <router-link to="login" class="nav-item r-item"><span>Join Now</span></router-link>
              </a>
            </p>
          </div>

        </div>
      </div>
    </div>
    
    <router-view></router-view>

    <footer class="footer is-primary" style=" background-color: #A020F0 !important; color: #fff !important">
      <div class="container">
        <div class="columns">
          <div class="column">
            <p>Proin ultrices massa sed mauris tincidunt mollis.</p>
          </div>
          <div class="column has-text-right">
              <a style="padding: 15px; " href="#" class="icon"><i style="color: #fff; " class="fab fa-whatsapp-square fa-2x"></i></a>
              <a style="padding: 15px; " href="#" class="icon"><i style="color: #fff;" class="fab fa-pinterest-square fa-2x"></i></a>
              <a style="padding: 15px; " href="#" class="icon"><i style="color: #fff;" class="fab fa-facebook-square fa-2x"></i></i></a>
              <a style="padding: 15px; " href="#" class="icon"><i style="color: #fff;" class="fab fa-instagram fa-2x"></i></a>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'app',
  data: function(){
    return{
      isActive: false
    }
  },
  methods:{
    toggleNav: function(){
      this.isActive = !this.isActive;
    }
  }
}
</script>

<style lang="sass">
@import '../node_modules/bulma/bulma.sass'

.nav
  background-color: #383838
  a:hover
    color: gray

.nav-left a 
  color: #fff
  font-weight: bold

a.r-item
  color:#C1C1C1
  padding: 0.5rem 1.75rem
  +mobile
    color: gray
    &:hover
      background-color: #F1F1F1

.nav-toggle span
  background-color: #A020F0 !important

.button-join
  color: #A020F0 !important
  border: 1px solid #A020F0 !important
  background: transparent

.nav-item:hover
  color: #A020F0 !important


</style>