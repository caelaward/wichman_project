<template>


   <!-- ======= About Section ======= -->
   <!-- <section id="about" class="about mt-4 mb-2">
    
      <div class="container" data-aos="fade-up">
     
        <div class="section-header">
          <h2>About Us</h2>
          <p>Learn More <span>About Us</span></p>
        </div>

        <div class="row gy-4">
          <div class="col-lg-7 position-relative about-img" style="background-image: url(https://cdn-thumbs.imagevenue.com/da/ce/7a/ME185QRK_b.jpg) ;" data-aos="fade-up" data-aos-delay="150">
            <div class="call-us position-absolute">
              <h4>Get in touch</h4>
              <p>+1 5589 55488 55</p>
            </div>
          </div>
          <div class="col-lg-4 d-flex align-items-end" data-aos="fade-up" data-aos-delay="300">
            <div class="content ps-0 ps-lg-5">
              <p class="fst-italic">
                A family based company, proudly and completely owned by woman of colour, we opened our doors in 2009. We strive to offer a professional service to all our clients and pride ourselves in the care and precision that we take when developing any type of event, be it as small as a children’s birthday or as big and detailed as a wedding or corporate activation. 
              </p>
              <ul>
                <li><i class="bi bi-check2-all"></i> Ullamco laboris nisi ut aliquip ex ea commodo consequat.</li>
                <li><i class="bi bi-check2-all"></i> Duis aute irure dolor in reprehenderit in voluptate velit.</li>
                <li><i class="bi bi-check2-all"></i> Ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate trideta storacalaperda mastiro dolore eu fugiat nulla pariatur.</li>
              </ul>
              <p>
                Ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
                velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident
              </p>

              
            </div>
          </div>
        </div>

      </div>


    
    </section>End About Section -->

   
  <div class="container-fluid" id="aboutImg"><h1 class="mt-5 ">About us</h1></div>
 <div class="container-fluid  mt-2" id="aboutPage">
   
    <div class="row mt-5">
    <div class="col" >
    <p>At BloubergLux, we're dedicated to helping you find your perfect home sweet home. Whether you're a first-time buyer, seasoned investor, or looking to sell your current property, we're here to guide you through every step of the journey.</p>
    </div>
    </div>
    <div class="row mt-5" id="Middle_about">
      <div class="col">
        <img src="https://cdn-thumbs.imagevenue.com/da/ce/7a/ME185QRK_b.jpg">
      </div>
    <div class="col" id="mission">
     <p> A family based company, proudly and completely owned by woman of colour, we opened our doors in 2009. We strive to offer a professional service to all our clients and pride ourselves in the care and precision that we take when developing any type of event, be it as small as a children’s birthday or as big and detailed as a wedding or corporate activation. </p>
    </div>
    </div> 

    <div class="row mt-5" id="Middle_about">
    <div class="col" id="mission">
     <p> A family based company, proudly and completely owned by woman of colour, we opened our doors in 2009. We strive to offer a professional service to all our clients and pride ourselves in the care and precision that we take when developing any type of event, be it as small as a children’s birthday or as big and detailed as a wedding or corporate activation. </p>
    </div>
    <div class="col">
        <img src="https://cdn-thumbs.imagevenue.com/da/ce/7a/ME185QRK_b.jpg">
      </div>
    </div> 

    <div class="row mt-5" id="Middle_about">
      <div class="col mb-5">
        <img src="https://cdn-thumbs.imagevenue.com/da/ce/7a/ME185QRK_b.jpg">
      </div>
    <div class="col" id="mission">
     <p> A family based company, proudly and completely owned by woman of colour, we opened our doors in 2009. We strive to offer a professional service to all our clients and pride ourselves in the care and precision that we take when developing any type of event, be it as small as a children’s birthday or as big and detailed as a wedding or corporate activation. </p>
    </div>
    </div> 
 </div>


    
    <FooterComp/>

     
</template>

<script>
import FooterComp from '../components/FooterComp.vue'
export default {
  components: {
    FooterComp,
    // NavComp
   
  }
  
}
</script>


<style scoped>
/*--------------------------------------------------------------
# About Section
--------------------------------------------------------------*/
.about .about-img {
  min-height: 500px;
}

.about h3 {
  font-weight: 700;
  font-size: 36px;
  margin-bottom: 30px;
  font-family: var(--font-secondary);
}

.about .call-us {
  left: 10%;
  right: 10%;
  bottom: 10%;
  background-color: #fff;
  box-shadow: 0px 2px 25px rgba(0, 0, 0, 0.08);
  padding: 20px;
  text-align: center;
}

.about .call-us h4 {
  font-size: 24px;
  font-weight: 700;
  margin-bottom: 5px;
  font-family: var(--font-default);
}

.about .call-us p {
  font-size: 28px;
  font-weight: 700;
  color: var(--color-primary);
}

.about .content ul {
  list-style: none;
  padding: 0;
}

.about .content ul li {
  padding: 0 0 8px 26px;
  position: relative;
}

.about .content ul i {
  position: absolute;
  font-size: 20px;
  left: 0;
  top: -3px;
  color: var(--color-primary);
}

.about .content p:last-child {
  margin-bottom: 0;
}

.about .play-btn {
  width: 94px;
  height: 94px;
  background: radial-gradient(var(--color-primary) 50%, rgba(206, 18, 18, 0.4) 52%);
  border-radius: 50%;
  display: block;
  position: absolute;
  left: calc(50% - 47px);
  top: calc(50% - 47px);
  overflow: hidden;
}

.about .play-btn:before {
  content: "";
  position: absolute;
  width: 120px;
  height: 120px;
  animation-delay: 0s;
  animation: pulsate-btn 2s;
  animation-direction: forwards;
  animation-iteration-count: infinite;
  animation-timing-function: steps;
  opacity: 1;
  border-radius: 50%;
  border: 5px solid rgba(206, 18, 18, 0.7);
  top: -15%;
  left: -15%;
  background: rgba(198, 16, 0, 0);
}

.about .play-btn:after {
  content: "";
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translateX(-40%) translateY(-50%);
  width: 0;
  height: 0;
  border-top: 10px solid transparent;
  border-bottom: 10px solid transparent;
  border-left: 15px solid #fff;
  z-index: 100;
  transition: all 400ms cubic-bezier(0.55, 0.055, 0.675, 0.19);
}

.about .play-btn:hover:before {
  content: "";
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translateX(-40%) translateY(-50%);
  width: 0;
  height: 0;
  border: none;
  border-top: 10px solid transparent;
  border-bottom: 10px solid transparent;
  border-left: 15px solid #fff;
  z-index: 200;
  animation: none;
  border-radius: 0;
}

.about .play-btn:hover:after {
  border-left: 15px solid var(--color-primary);
  transform: scale(20);
}

@keyframes pulsate-btn {
  0% {
    transform: scale(0.6, 0.6);
    opacity: 1;
  }

  100% {
    transform: scale(1, 1);
    opacity: 0;
  }
}

h2{
   color:rgb(175,148,83)
}

</style>