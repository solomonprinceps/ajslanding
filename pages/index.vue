<template>
<div class="page-wrapper">
  <div class="nav-component">
    <img src="~/assets/image/weblogo.png" alt="AJS LOGO" />
    <button type="button" class="btn btn-primary btn-lg">Request Access</button>
  </div>
  <div class="container-fluid">
    <!-- <div v-if="$device.isDesktopOrTablet"> </div> -->
    <div class="row sectionone">
      <div class="col-lg-12 col-md-12 col-sm-12 mb-3">
        <div class="firstblock">
          <h1 class="h1-text"><span class="ajs"> Ajo Suites </span> Scales your Ajo business with a single integration.</h1>
          <p class="mt-3 p-text">Ajo Suites gives you instant access to multiple savers, saving plans and withdrawal with options for payment collections.</p>
          <button type="button" class="btn btn-primary btn-lg navbutton mt-3 ">Request Access</button>
        </div>
      </div>
      <!-- <div class="col-lg-6 col-md-12 col-sm-12">
        <div class="block90">
          <b-img src="~/assets/image/ajs.png" class="shadow bg-white rounded" fluid-grow alt="Fluid-grow image"></b-img>
        </div>
      </div> -->
    </div>
  </div>  
  <div class="container-fluid" style="background: #F3F9FF;">
    <div style="height: 60px;"></div>
    <div class="row">
      <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12 text-center">
        <p class="section2header">Payments optimised for ambitious businesses.</p>
      </div>
    </div>
    <div class="row">
      <div class="col-lg-3 col-md-12">
        <div class="sectioncard">
          <div class="iconbox">
            <Shield style="color: #13528b;" />
          </div>
          <span>Security guarantee for your <b>esusu</b> business. </span>
          <p>Ensure the best industry standard to security for savings, saver and withdrawal records that keeps your business up 24/7.</p>
        </div>
      </div>
      <div class="col-lg-3 col-md-12">
        <div class="sectioncard">
          <div class="iconbox">
            <BookFill style="color: #13528b;" />
          </div>
          <span>Transparency guarantee for your <b>esusu</b> business. </span>
          <p>Clean and verifiable record keeping for both <b>AJO</b> business and <b>AJO</b> business customer which aids swift reconciliation.</p>
        </div>
      </div>
      <div class="col-lg-3 col-md-12">
        <div class="sectioncard">
          
          <div class="iconbox">
            <Printer style="color: #13528b;" />
          </div>
          <span>Issue receipt of payment for yout <b>esusu</b> business. </span>
          <p>Increase customer trust in <b>AJO</b> business and reduce operations cost with a combination of SMS, Email, App notifcation and receipt.</p>
        </div>
      </div>
      <div class="col-lg-3 col-md-12">
        <div class="sectioncard">
          <div class="iconbox">
            <CloudCheck style="color: #13528b;" />
          </div>
          <span>secure your <b>esusu</b> business with the latest cloud technology. </span>
          <p>Supercharge how your <b>THRIFT</b> collection business. with the latest cloud infrastructure and technology available today..</p>
        </div>
      </div>
    </div>

    <div class="col-md-12 p-5 d-flex justify-content-center">
      <b-img src="~/assets/image/ajs.png" class="shadow bg-white rounded" style="width: 80%;" fluid-grow alt="Fluid-grow image"></b-img>
    </div>
    
  </div>

  <div class="container-fluid footer"> 
    <div class="row">
      <div class="col-md-4 p-3">
        <img src="~/assets/image/ajsuite1.png" style="height: 100px; width: 100px; border-raduis: 100%;" alt="AJS LOGO" />
        <div>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, doloribus! Rem, pariatur nisi non temporibus minus explicabo reiciendis modi tempore a beatae exercitationem ullam nihil similique voluptatem totam vero voluptate!
        </div>
      </div>
    </div>
  </div>
  
</div>
</template>

<script>
import Shield  from "~/assets/svg/shield.svg/?inline";
import BookFill from '~/assets/svg/book-fill.svg/?inline'
import Printer from '~/assets/svg/printer.svg/?inline'
import CloudCheck from '~/assets/svg/cloud-check.svg/?inline'
export default {
  name: 'IndexPage',
  components: { 
    Shield,
    BookFill,
    Printer,
    CloudCheck
  },
}
</script>
