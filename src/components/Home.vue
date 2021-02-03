<template>
  <div class="home">
    <section class="hero">
      <div class="hero-body">
        <div class="container">
          <h1 class="title" style="font-weight: bold">{{ heading }}</h1>
          <div class="is-two-thirds column is-paddingless">
            <h2 class="subtitle is-4">{{ subheading }}</h2>
          </div>
          <a href="#" id="learn" class="button is-large is-primary">Our Services</a>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="container" style="padding-bottom: 35px">
        <div class="columns pd is-desktop">
          <div class="column is-1 has-text-centered">
            <i style="color: #A020F0 !important; font-size: 50px" class="fa fa-cog is-primary"></i>
          </div>
           <div class="column is-two-third-desktop">
            <p class="title"><strong>Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nulla feugiat mauris vitae libero dimentum.</strong></p>
          </div>
          <div class="column is-tow-third-desktop">
            <p class="title">Etiam sit amet est ultricies, iaculis arcu ac, feugiat dui. Suspendisse porttitor, lacus id egestas lacinia, arcu odio semper augue, in ultrices mi dui eget velit.</p>
          </div>
        </div>
      </div>

      <div class="columns pd">
        <div class="column">
          <div class="card">
            <div class="card-content">
              <p class="title">
              “If you can dream it, you can do it. Always remember that this whole thing started with a dream and a mouse.”</p>
                <p class="subtitle">
                  - Walt Disney
                </p>
            </div>
          </div>
        </div>

        <div class="column">
          <div class="card">
            <div class="card-content">
              <p class="title">
              “And in the end, it's not the years in your life that count. It's the life in your years.”</p>
                <p class="subtitle">
                  - Abraham Lincoln
                </p>
            </div>
          </div>
        </div>
        
        <div class="column">
          <div class="card">
            <div class="card-content">
              <p class="title">
              “I was born with an enormous need for affection, and a terrible need to give it.”</p>
                <p class="subtitle">
                  - Audrey Hepburn
                </p>
            </div>
          </div>
        </div>
      </div>


    </section>
  </div>
</template>

<script>
export default {
  name: 'home',
  data(){
    return{
      heading: 'Maecenas nec turpis quis',
      subheading: 'Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nulla feugiat mauris vitae libero dimentum.'
    }
  }
}
</script>

<style lang="sass" scoped>
@import '../mq'

#learn
  background-color: #A020F0 !important

.hero
  background: url('../assets/bg-void.jpg')
  background-size: cover
  background-repeat: no-repeat

  .title
    .mobile 
      font-weight: bold
    .tablet
      font-size: 2.5rem
    .desktop
      font-size: 4rem
      margin-top: 2rem

  h2
    margin: 1.5rem 0 2rem 0 !important
    
  #learn
    +desktop
      margin-bottom: 2rem

  .pd
    +tablet
      padding: 2rem 0

  
</style>
