<template>
  <div class="faq">
    <section class="hero">
      <div class="hero-body">
        <div class="container">
          <h1 class="title" style="font-weight: bold">FAQ</h1><br>
          <h2 class="subtitle is-4">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras lorem tellus, tincidunt ut eros ac,<br> venenatis eleifend turpis. </h2>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="container">
        <div class="columns pd" style="padding-top: 0">
          
          <div class="column">
            <div class="column is-two-third">
              <div class="card">
                <div class="card-content">
                  <p class="title">Quisque diam turpis, mattis non lectus et?</p>
                  <p class="answer">Cras et neque accumsan, mattis magna a, aliquam nisi. Sed in enim consectetur, blandit magna at, volutpat turpis. Duis sagittis dolor quis nulla consequat lobortis</p>
                </div>
              </div>
            </div>
          </div>

          <div class="column">
            <div class="column is-two-third">
              <div class="card">
                <div class="card-content">
                  <p class="title">Quisque diam turpis, mattis non lectus et?</p>
                  <p class="answer">Cras et neque accumsan, mattis magna a, aliquam nisi. Sed in enim consectetur, blandit magna at, volutpat turpis. Duis sagittis dolor quis nulla consequat lobortis</p>
                </div>
              </div>
            </div>
          </div>

          <div class="column">
            <div class="column is-two-third">
              <div class="card">
                <div class="card-content">
                  <p class="title">Quisque diam turpis, mattis non lectus et?</p>
                  <p class="answer">Cras et neque accumsan, mattis magna a, aliquam nisi. Sed in enim consectetur, blandit magna at, volutpat turpis. Duis sagittis dolor quis nulla consequat lobortis</p>
                </div>
              </div>
            </div>
          </div>     
        </div>

         <div class="columns pd">
          
          <div class="column">
            <div class="column is-two-third">
              <div class="card">
                <div class="card-content">
                  <p class="title">Quisque diam turpis, mattis non lectus et?</p>
                  <p class="answer">Cras et neque accumsan, mattis magna a, aliquam nisi. Sed in enim consectetur, blandit magna at, volutpat turpis. Duis sagittis dolor quis nulla consequat lobortis</p>
                </div>
              </div>
            </div>
          </div>

          <div class="column">
            <div class="column is-two-third">
              <div class="card">
                <div class="card-content">
                  <p class="title">Quisque diam turpis, mattis non lectus et?</p>
                  <p class="answer">Cras et neque accumsan, mattis magna a, aliquam nisi. Sed in enim consectetur, blandit magna at, volutpat turpis. Duis sagittis dolor quis nulla consequat lobortis</p>
                </div>
              </div>
            </div>
          </div>

          <div class="column">
            <div class="column is-two-third">
              <div class="card">
                <div class="card-content">
                  <p class="title">Quisque diam turpis, mattis non lectus et?</p>
                  <p class="answer">Cras et neque accumsan, mattis magna a, aliquam nisi. Sed in enim consectetur, blandit magna at, volutpat turpis. Duis sagittis dolor quis nulla consequat lobortis</p>
                </div>
              </div>
            </div>
          </div>     
        </div>

         <div class="columns pd">
          
          <div class="column">
            <div class="column is-two-third">
              <div class="card">
                <div class="card-content">
                  <p class="title">Quisque diam turpis, mattis non lectus et?</p>
                  <p class="answer">Cras et neque accumsan, mattis magna a, aliquam nisi. Sed in enim consectetur, blandit magna at, volutpat turpis. Duis sagittis dolor quis nulla consequat lobortis</p>
                </div>
              </div>
            </div>
          </div>

          <div class="column">
            <div class="column is-two-third">
              <div class="card">
                <div class="card-content">
                  <p class="title">Quisque diam turpis, mattis non lectus et?</p>
                  <p class="answer">Cras et neque accumsan, mattis magna a, aliquam nisi. Sed in enim consectetur, blandit magna at, volutpat turpis. Duis sagittis dolor quis nulla consequat lobortis</p>
                </div>
              </div>
            </div>
          </div>

          <div class="column">
            <div class="column is-two-third">
              <div class="card">
                <div class="card-content">
                  <p class="title">Quisque diam turpis, mattis non lectus et?</p>
                  <p class="answer">Cras et neque accumsan, mattis magna a, aliquam nisi. Sed in enim consectetur, blandit magna at, volutpat turpis. Duis sagittis dolor quis nulla consequat lobortis</p>
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
  name: 'faq',

}
</script>

<style lang="sass" scoped>
@import '../mq'

.pd
  padding: 2.5em 0 1.5em 0

.answer
  margin-top: 10px !important
  color: gray

.columns
  flex-wrap: wrap

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
