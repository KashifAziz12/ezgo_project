<template>
  <div>
    <section id="about">
      <div id="container">
        <div class="row">
          <div class="col-md-6 col-sm-6">
            <div
              class="info-left"
              data-aos="fade-right"
              data-aos-duration="2000"
            >
            <br/> <br/>
              <img class="phone-align-image" src="../assets/about-us-sm.jpg" alt="" />
            </div>
          </div>
          <div class="col-md-6 col-sm-6">
            <div
              class="info-right"
              data-aos="fade-left"
              data-aos-duration="2000"
            >
              <h2 class="phone-align-text">A little more about Us...</h2>
              <p class="phone-align-text">
                We, at Elite Transportation, have been working our hardest to earn our reputation in the industry over the last few years. Since founding, we have expanded to be able to deliver not just to all 50 states, but also to Canada and Mexico, making us the best option for North American Delivery.
                <br/>
                <p class="phone-align-text">We’ve come to offer all services form LTL-shipping up to truckloads of trailers, to be able to accommodate for every possible service you are looking for.</p>
              </p>
              <br />
              <div class="phone-align-btn">
              <b-button @click="toContactForm()" class="btn btn-primary">Contact me</b-button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <hr />
    <section id="info2">
      <div id="container">
        <div class="row">
          <div class="col-md-6 col-sm-6">
            <div
              class="info-left"
              data-aos="fade-right"
              data-aos-duration="2000"
            >
              <h2>Shipping Consultation</h2>
              <p>
                The communication in our company is unmatched, so you have full control over what gets decided, our management and staff will then help you to take all the necessary steps towards your dream of becoming everyone’s reality. If you are unsure if you need LTL- or FLT-shipping, our team of experts will assist you in making the best-informed decision for your business needs.
                <br/> <br/>
                <ul class="b">
                  <li>Brainstorming</li>
                  <li>Approaching</li>
                  <li>Adjusting</li>
              </ul>
              </p>
            </div>
          </div>
          <div class="col-md-6 col-sm-6">
            <div
              class="info-right"
              data-aos="fade-left"
              data-aos-duration="2000"
            >
              <h2>Address</h2>
              <p>
                Unit 1007, Apt 2350 <br/>
                Brichmount & Shepherd intersection <br/>
                Toronto, ON 
              </p>
              <img class="animated-gif" src="" alt="">
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
<script>
export default {
  methods: {
    toContactForm() {
      document.getElementById('contact').scrollIntoView({
        behavior: 'smooth',
        block: 'end',
      })
    }
  }
}
</script>
<style scoped>
img {
  width: 90%;
  margin-left: 60px;
  size: 50%;
}
#about .info-right {
  margin-top: 90px;
}
section {
  margin-top: 70px;
  font-size: 16px;
  overflow-x: hidden;
}
#info2 {
  margin: 20px 60px 60px 70px;
}
ul.b {
  list-style-type: square;
}
@media (max-width: 550px) {
  .phone-align-text{
  padding-left: 30px 
}
.phone-align-btn{
  text-align: center;
}
.phone-align-image{
  padding-right: 40px
}
}
img.animated-gif{
  width: 120px;
  height: auto;
}


</style>
