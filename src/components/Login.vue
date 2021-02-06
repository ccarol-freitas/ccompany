<template>
  <section class="section">
  <div class="container ">
    <mdb-row>
     <mdb-col class="col-4 col-md-3" > </mdb-col>
      <mdb-col class="col-3 col-md-6 " >
        <mdb-card>
          <mdb-card-body class="mx-6">
            <div class="text-center">
              <h3 class="dark-grey-text mb-5"><strong>Sign in</strong></h3>
            </div>
            <mdb-input style="color: #A020F0 !important" label="Your email" type="email"/>
            <mdb-input style="color: #A020F0 !important" label="Your password" type="password" containerClass="mb-0"/>
            <p style="color: #A020F0 !important" class="font-medium purple-text d-flex justify-content-end pb-3">Forgot <a style="color: #A020F0 !important" href="#" class="purple-text ml-1"> Password?</a></p>
            <div class="text-center mb-3">
              <mdb-btn  type="button" gradient="purple" rounded class="btn-block z-depth-1a">Sign in</mdb-btn>
            </div>
            <p style="color: #A020F0 !important" class="font-medium dark-grey-text text-right d-flex justify-content-center mb-3 pt-2"> or Sign in with:</p>
            <div class="row my-3 d-flex justify-content-center">
              <mdb-btn type="button" color="white" rounded class="mr-md-3 z-depth-1a"><mdb-icon fab icon="facebook" class="purple-text text-center"/></mdb-btn>
              <mdb-btn type="button" color="white" rounded class="mr-md-3 z-depth-1a"><mdb-icon fab icon="twitter" class="purple-text"/></mdb-btn>
              <mdb-btn type="button" color="white" rounded class="z-depth-1a"><mdb-icon fab icon="google-plus" class="purple-text"/></mdb-btn>
            </div>
          </mdb-card-body>
          <mdb-modal-footer class="mx-5 pt-3 mb-1">
            <p class="font-medium grey-text d-flex justify-content-end">Not a member? <a style="color: #A020F0 !important" href="#" class="purple-text ml-1"> Sign Up</a></p>
          </mdb-modal-footer>
        </mdb-card>
      </mdb-col>
      <mdb-col class="col-4" > </mdb-col>

    </mdb-row>
    </div>
  </section>
</template>

<script>
  import { mdbRow, mdbCol, mdbCard, mdbCardBody, mdbInput, mdbBtn, mdbIcon, mdbModal, mdbModalBody, mdbModalFooter } from 'mdbvue';
  export default {
    name: 'FormsPage',
    components: {
      mdbRow,
      mdbCol,
      mdbCard,
      mdbCardBody,
      mdbInput,
      mdbBtn,
      mdbIcon,
      mdbModal,
      mdbModalBody,
      mdbModalFooter
    },
    data() {
      return {
        showModal: false
      };
    }
  }
</script>

<style>

h3{
    font-size: 21px;
}
label{
    color: #ac84c5 !important;
}
  .form-elegant .font-medium {
    font-size: 2.5rem; }

  .form-elegant .z-depth-1a {
    -webkit-box-shadow: 0 2px 5px 0 #ac84c5 , 0 4px 12px 0 rgb(160, 32, 240);
    box-shadow: 0 2px 5px 0 rgb(185, 121, 224), 0 4px 12px 0 rgb(160, 32, 240); }

  .form-elegant .z-depth-1-half,
  .form-elegant .btn:hover {
    -webkit-box-shadow: 0 5px 11px 0 rgb(160, 32, 240), 0 4px 15px 0 rgb(160, 32, 240);
    box-shadow: 0 5px 11px 0 rgb(160, 32, 240), 0 4px 15px 0 rgb(160, 32, 240); }
    .container{
        max-width: 1000px;
    margin: 0 auto;
    }
</style>