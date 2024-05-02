<template>
    <div>
        <h1>Work</h1>

    </div>

    <!-- ======= Venue Section ======= -->
    <section id="venue">

<div class="container-fluid" data-aos="fade-up">

  <div class="section-header">
    <h2>Event Venue</h2>
    <p>Event venue location info and gallery</p>
  </div>

  <div class="row g-0">
    <div class="col-lg-6 venue-map">
      <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d12097.433213460943!2d-74.0062269!3d40.7101282!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xb89d1fe6bc499443!2sDowntown+Conference+Center!5e0!3m2!1smk!2sbg!4v1539943755621" frameborder="0" style="border:0" allowfullscreen></iframe>
    </div>

    <div class="col-lg-6 venue-info">
      <div class="row justify-content-center">
        <div class="col-11 col-lg-8 position-relative">
          <h3>Downtown Conference Center, New York</h3>
          <p>Iste nobis eum sapiente sunt enim dolores labore accusantium autem. Cumque beatae ipsam. Est quae sit qui voluptatem corporis velit. Qui maxime accusamus possimus. Consequatur sequi et ea suscipit enim nesciunt quia velit.</p>
        </div>
      </div>
    </div>
  </div>

</div>

<div class="container venue-gallery-container" data-aos="fade-up" data-aos-delay="100">
  <div class="row">

    <div class="col-lg-3 col-md-4">
      <div class="venue-gallery">
       
          <img src="https://i.ibb.co/g4F1L9N/imgEX.jpg" alt="" class="img-fluid">
      
      </div>
    </div>

    <div class="col-lg-3 col-md-4">
      <div class="venue-gallery">
       
          <img src="https://i.ibb.co/g4F1L9N/imgEX.jpg" alt="" class="img-fluid">
       
      </div>
    </div>

    <div class="col-lg-3 col-md-4">
      <div class="venue-gallery">

          <img src="https://i.ibb.co/g4F1L9N/imgEX.jpg" alt="" class="img-fluid">
       
      </div>
    </div>

    <div class="col-lg-3 col-md-4">
      <div class="venue-gallery">
        
          <img src="https://i.ibb.co/g4F1L9N/imgEX.jpg" alt="" class="img-fluid">
      
      </div>
    </div>

    <div class="col-lg-3 col-md-4">
      <div class="venue-gallery">
        
          <img src="https://i.ibb.co/g4F1L9N/imgEX.jpg" alt="" class="img-fluid">
        
      </div>
    </div>

    <div class="col-lg-3 col-md-4">
      <div class="venue-gallery">
        
          <img src="https://i.ibb.co/g4F1L9N/imgEX.jpg" alt="" class="img-fluid">
       
      </div>
    </div>

    <div class="col-lg-3 col-md-4">
      <div class="venue-gallery">
        
          <img src="https://i.ibb.co/g4F1L9N/imgEX.jpg" alt="" class="img-fluid">
        
      </div>
    </div>

    <div class="col-lg-3 col-md-4">
      <div class="venue-gallery">
       
          <img src="https://i.ibb.co/g4F1L9N/imgEX.jpg" alt="" class="img-fluid">
       
      </div>
    </div>

  </div>
</div>

</section><!-- End Venue Section -->
</template>

<style scoped>
/*--------------------------------------------------------------
# Venue Section
--------------------------------------------------------------*/
#venue {
  padding: 60px 0;
}

#venue .container-fluid {
  margin-bottom: 3px;
}

#venue .venue-map iframe {
  width: 100%;
  height: 100%;
  min-height: 300px;
}

#venue .venue-info {
  /* background: url("../img/venue-info-bg.jpg") top center no-repeat; */
  background-size: cover;
  position: relative;
  padding-top: 60px;
  padding-bottom: 60px;
}

#venue .venue-info:before {
  content: "";
  background: rgba(13, 20, 41, 0.8);
  position: absolute;
  bottom: 0;
  top: 0;
  left: 0;
  right: 0;
}

#venue .venue-info h3 {
  font-size: 36px;
  font-weight: 700;
  color: #fff;
}

@media (max-width: 574px) {
  #venue .venue-info h3 {
    font-size: 24px;
  }
}

#venue .venue-info p {
  color: #fff;
  margin-bottom: 0;
}

#venue .venue-gallery-container {
  padding-right: 12px;
}

#venue .venue-gallery {
  overflow: hidden;
  border-right: 3px solid #fff;
  border-bottom: 3px solid #fff;
}

#venue .venue-gallery img {
  transition: all ease-in-out 0.4s;
}

#venue .venue-gallery:hover img {
  transform: scale(1.1);
}
</style>