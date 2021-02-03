<template>
    <div class="features">
        <section class="hero">
            <div class="hero-body" style="padding-bottom: 20px">
                <div class="container">
                    <h1 class="title"><strong>{{ heading }}</strong></h1>
                    <div class="is-two-thirds column is-paddingless">
                        <h2 class="subtitle is-4">{{ subheading }}</h2>
                    </div>
                </div>
            </div>
        </section>

        <section class="section">
            <div class="container">
                <div class="columns pd is-desktop">
                    <div class="columns pd">
                        <div class="column">
                            <div class="card" style="box-shadow: 10px 10px 5px #c1c1c1 !important">
                                <div class="card-content">
                                    <p class="title" style="padding-bottom: 25px">Veniam adipisicing</p>
                                    <p class="subtitle">Aliquip sit sint in consectetur elit ea consectetur tempor ad labore et nisi. Dolore magna labore occaecat ullamco eu ad mollit enim commodo eu. Sunt in mollit sit cupidatat velit do tempor commodo ea. Commodo commodo consequat exercitation anim et culpa aute occaecat sunt aliquip nisi.</p>
                                </div>
                            </div>
                        </div>

                        <div class="column">
                            <div class="card" style="box-shadow: 10px 10px 5px #c1c1c1 !important">
                                <div class="card-content">
                                    <p class="title" style="padding-bottom: 25px">Veniam adipisicing</p>
                                    <p class="subtitle">Aliquip sit sint in consectetur elit ea consectetur tempor ad labore et nisi. Dolore magna labore occaecat ullamco eu ad mollit enim commodo eu. Sunt in mollit sit cupidatat velit do tempor commodo ea. Commodo commodo consequat exercitation anim et culpa aute occaecat sunt aliquip nisi.</p>
                                </div>
                            </div>
                        </div>

                        <div class="column">
                            <div class="card" style="box-shadow: 10px 10px 5px #c1c1c1 !important">
                                <div class="card-content">
                                    <p class="title" style="padding-bottom: 25px">Veniam adipisicing</p>
                                    <p class="subtitle">Aliquip sit sint in consectetur elit ea consectetur tempor ad labore et nisi. Dolore magna labore occaecat ullamco eu ad mollit enim commodo eu. Sunt in mollit sit cupidatat velit do tempor commodo ea. Commodo commodo consequat exercitation anim et culpa aute occaecat sunt aliquip nisi.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>


         <section class="section">
            <div class="container">
                <div class="columns pd is-desktop" style="padding-bottom: 20px">
                    <div class="columns pd">
                        <div class="column">
                            <div class="card">
                                <div class="card-content">
                                     <h6><strong>Sunt in mollit</strong></h6>
                                    <p class="">Dolore magna labore occaecat ullamco eu ad mollit enim commodo eu. Sunt in mollit sit cupidatat velit do tempor commodo ea.</p>
                                </div>
                            </div>
                        </div>

                        <div class="column">
                            <div class="card">
                                <div class="card-content">
                                    <h6><strong>Sunt in mollit</strong></h6>
                                    <p class="">Dolore magna labore occaecat ullamco eu ad mollit enim commodo eu. Sunt in mollit sit cupidatat velit do tempor commodo ea.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="columns pd is-desktop" style="padding-bottom: 20px">
                    <div class="columns pd">
                        <div class="column">
                            <div class="card">
                                <div class="card-content">
                                    <h6><strong>Sunt in mollit</strong></h6>
                                    <p class="">Dolore magna labore occaecat ullamco eu ad mollit enim commodo eu. Sunt in mollit sit cupidatat velit do tempor commodo ea.</p>
                                </div>
                            </div>
                        </div>

                        <div class="column">
                            <div class="card">
                                <div class="card-content">
                                    <h6><strong>Sunt in mollit</strong></h6>
                                    <p class="">Dolore magna labore occaecat ullamco eu ad mollit enim commodo eu. Sunt in mollit sit cupidatat velit do tempor commodo ea.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </section>
    </div>
</template>

<script>
export default {
  name: 'features',
  data(){
    return{
      heading: 'Features that fit',
      subheading: 'Ut nec pellentesque sapien. Proin et mauris nulla. Etiam ornare turpis ut magna placerat, malesuada porta purus maximus.'
    }
  }
}
</script>

<style lang="sass" scoped>
@import '../mq'

.hero
  background: url('../assets/bg-features.jpg')
  background-size: cover
  background-repeat: no-repeat

.container h1, h2
  color: #fff !important

.container h2
  font-weight: 400 !important

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

  .pd
    +tablet
      padding: 2rem 0
    

</style>