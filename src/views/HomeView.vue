<template>

    <!-- <NavComp/> -->
  <div class="container-fluid">
    <div class="box" >
      <h1 >Wichman and Co Event Planning</h1>
      <p class="mid">Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet repellendus veniam voluptatibus ducimus eligendi dolore asperiores soluta ipsa voluptatum, laborum aspernatur rem. Nihil.</p>
       <router-link to="/about" @click="scrollToTop()">Learn more</router-link>
    </div>
  </div>
  
  <div class="blank">
  
  
  <!-- <div id="default-carousel" class="relative w-full" data-carousel="slide">
  Carousel wrapper
  <div class="relative h-56 overflow-hidden rounded-lg md:h-96">
      Item 1
      <div class="hidden duration-700 ease-in-out flex items-center justify-center" data-carousel-item>
          <blockquote class="text-xl italic font-semibold text-gray-900 dark:text-white text-center">
              <svg class="w-8 h-8 text-gray-400 dark:text-white-600 mb-4" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 18 14">
                  <path d="M6 0H2a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h4v1a3 3 0 0 1-3 3H2a1 1 0 0 0 0 2h1a5.006 5.006 0 0 0 5-5V2a2 2 0 0 0-2-2Zm10 0h-4a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h4v1a3 3 0 0 1-3 3h-1a1 1 0 0 0 0 2h1a5.006 5.006 0 0 0 5-5V2a2 2 0 0 0-2-2Z"/>
              </svg>
              <p class="text-white">"Flowbite is just awesome. It contains tons of predesigned components and pages starting from login screen to complex dashboard. Perfect choice for your next SaaS application."</p>
          </blockquote>
      </div>
  
      Item 2
      <div class="hidden duration-700 ease-in-out flex items-center justify-center" data-carousel-item>
          <blockquote class="text-xl italic font-semibold text-gray-900 dark:text-white text-center">
              <svg class="w-8 h-8 text-gray-400 dark:text-white-600 mb-4" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 18 14">
                  <path d="M6 0H2a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h4v1a3 3 0 0 1-3 3H2a1 1 0 0 0 0 2h1a5.006 5.006 0 0 0 5-5V2a2 2 0 0 0-2-2Zm10 0h-4a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h4v1a3 3 0 0 1-3 3h-1a1 1 0 0 0 0 2h1a5.006 5.006 0 0 0 5-5V2a2 2 0 0 0-2-2Z"/>
              </svg>
              <p class="text-white">"You Flowbite is just awesome. It contains tons of predesigned components and pages starting from login screen to complex dashboard. Perfect choice for your next SaaS application."</p>
          </blockquote>
      </div>
  
      Item 3
      <div class="hidden duration-700 ease-in-out flex items-center justify-center" data-carousel-item>
          <blockquote class="text-xl italic font-semibold text-gray-900 dark:text-white text-center">
              <svg class="w-8 h-8 text-gray-400 dark:text-white-600 mb-4" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 18 14">
                  <path d="M6 0H2a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h4v1a3 3 0 0 1-3 3H2a1 1 0 0 0 0 2h1a5.006 5.006 0 0 0 5-5V2a2 2 0 0 0-2-2Zm10 0h-4a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h4v1a3 3 0 0 1-3 3h-1a1 1 0 0 0 0 2h1a5.006 5.006 0 0 0 5-5V2a2 2 0 0 0-2-2Z"/>
              </svg>
              <p class="text-white">"OK Flowbite is just awesome. It contains tons of predesigned components and pages starting from login screen to complex dashboard. Perfect choice for your next SaaS application."</p>
          </blockquote>
      </div>
      Item 4
      <div class="hidden duration-700 ease-in-out flex items-center justify-center" data-carousel-item>
          <blockquote class="text-xl italic font-semibold text-gray-900 dark:text-white text-center">
              <svg class="w-8 h-8 text-gray-400 dark:text-white-600 mb-4" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 18 14">
                  <path d="M6 0H2a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h4v1a3 3 0 0 1-3 3H2a1 1 0 0 0 0 2h1a5.006 5.006 0 0 0 5-5V2a2 2 0 0 0-2-2Zm10 0h-4a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h4v1a3 3 0 0 1-3 3h-1a1 1 0 0 0 0 2h1a5.006 5.006 0 0 0 5-5V2a2 2 0 0 0-2-2Z"/>
              </svg>
              <p class="text-white">"Yasis Flowbite is just awesome. It contains tons of predesigned components and pages starting from login screen to complex dashboard. Perfect choice for your next SaaS application."</p>
          </blockquote>
      </div>
      Item 5
      <div class="hidden duration-700 ease-in-out flex items-center justify-center" data-carousel-item>
          <blockquote class="text-xl italic font-semibold text-gray-900 dark:text-white text-center">
              <svg class="w-8 h-8 text-gray-400 dark:text-white-600 mb-4" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 18 14">
                  <path d="M6 0H2a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h4v1a3 3 0 0 1-3 3H2a1 1 0 0 0 0 2h1a5.006 5.006 0 0 0 5-5V2a2 2 0 0 0-2-2Zm10 0h-4a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h4v1a3 3 0 0 1-3 3h-1a1 1 0 0 0 0 2h1a5.006 5.006 0 0 0 5-5V2a2 2 0 0 0-2-2Z"/>
              </svg>
              <p class="text-white">"last Flowbite is just awesome. It contains tons of predesigned components and pages starting from login screen to complex dashboard. Perfect choice for your next SaaS application."</p>
          </blockquote>
      </div>
  </div>
  Slider indicators
  <div class="absolute z-30 flex -translate-x-1/2 bottom-5 left-1/2 space-x-3 rtl:space-x-reverse mt-5">
      <button type="button" class="w-3 h-3 rounded-full" aria-current="true" aria-label="Slide 1" data-carousel-slide-to="0"></button>
      <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 2" data-carousel-slide-to="1"></button>
      <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 3" data-carousel-slide-to="2"></button>
      <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 4" data-carousel-slide-to="3"></button>
      <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 5" data-carousel-slide-to="4"></button>
  </div>
  Slider controls
  <button type="button" class="absolute top-0 start-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none" data-carousel-prev>
      <span class="inline-flex items-center justify-center w-10 h-10 rounded-full bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
          <svg class="w-4 h-4 text-white dark:text-gray-800 rtl:rotate-180" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 6 10">
              <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 1 1 5l4 4"/>
          </svg>
          <span class="sr-only">Previous</span>
      </span>
  </button>
  <button type="button" class="absolute top-0 end-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none" data-carousel-next>
      <span class="inline-flex items-center justify-center w-10 h-10 rounded-full bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
          <svg class="w-4 h-4 text-white dark:text-gray-800 rtl:rotate-180" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 6 10">
              <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 9 4-4-4-4"/>
          </svg>
          <span class="sr-only">Next</span>
      </span>
  </button>
  </div>
  
  
  -->
  <section class="testimonial text-center">
  <div class="container">
      <div class="heading white-heading">
          Reviews
      </div>
      <div id="testimonial4" class="carousel slide testimonial4_indicators testimonial4_control_button thumb_scroll_x swipe_x" data-bs-ride="carousel" data-bs-pause="hover" data-bs-interval="5000">
          <div class="carousel-inner">
              <div class="carousel-item active">
                  <div class="testimonial4_slide">
                      <!-- <img src="https://i.ibb.co/8x9xK4H/team.jpg" class="img-circle img-responsive" /> -->
                      <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</p>
                      <h4>Client 1</h4>
                  </div>
              </div>
              <div class="carousel-item">
                  <div class="testimonial4_slide">
                      <!-- <img src="https://i.ibb.co/8x9xK4H/team.jpg" class="img-circle img-responsive" /> -->
                      <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</p>
                      <h4>Client 2</h4>
                  </div>
              </div>
              <div class="carousel-item">
                  <div class="testimonial4_slide">
                      <!-- <img src="https://i.ibb.co/8x9xK4H/team.jpg" class="img-circle img-responsive" /> -->
                      <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</p>
                      <h4>Client 3</h4>
                  </div>
              </div>
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#testimonial4" data-bs-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#testimonial4" data-bs-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
          </button>
      </div>
  </div>
  </section>
  
  
  </div>
  
  
  
  <div class="container-fluid second">
  <!-- <div class="item">
  <div class="img img-first"></div>
  <div class="card">
    <h3>Rock climbing</h3>
    <p>The goal is to reach the summit of a formation or the endpoint of a usually pre-defined route without falling</p>
    <a href="#">Learn more</a>
  </div>
  </div> -->
  <div class="item">
  
  <div class="card">
    <h3>Services</h3>
    <p  class="txt">Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe, eos perspiciatis praesentium inventore repellendus sequi porro quidem impedit optio iure quis, explicabo obcaecati eveniet eius distinctio. Officia nihil amet in.</p>
    <router-link to="/service" @click="scrollToTop()">Learn more</router-link>
  </div>
  </div>
  <div class="item">
  
  <div class="card">
    <h3>Our work</h3>
    <p class="txt">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Eos consequatur autem iure placeat possimus quo accusantium fugit, necessitatibus nesciunt, cum perferendis eaque id commodi, maiores voluptatem aliquid neque perspiciatis .</p>
    <router-link to="/projects" @click="scrollToTop()">Learn more</router-link>
  
  </div>
  </div>
  </div>
  
  <div class="blanks">
  <FooterComp/>
  
  </div>
  </template>
  
  <script>
  
  import FooterComp from '../components/FooterComp.vue'
  // import NavComp from '../components/NavComp.vue'
  
  
  export default {
  
  components: {
  FooterComp,
  // NavComp
  
  },
  methods: {
    scrollToTop() {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    }
  }
  }
  </script>
  
  <style scoped>
  
  @import url('https://fonts.googleapis.com/css2?family=Red+Hat+Text:wght@400;700&display=swap');
  
  :root{
  --color: #333; 
  }
  
  body {
  font-family: 'Red Hat Text', sans-serif;
  }
  
  .container-fluid {
  text-align: center;
  color: white;
  width: 100%;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background-image: url(https://i.ibb.co/tPv85zH/frontImg.jpg);
  background-size: cover;
  background-position: center;
  
  /*  this is where the magic happens:  */
  background-attachment: fixed;
  }
  
  h1 {
  font-weight: 700;
  font-size: 3rem;
  }
  
  .txt {
  max-width: 52ch;
  flex-wrap: wrap;
  line-height: 1.5;
  /* margin-left:155px; */
  padding: 1em;
  text-align: center; /* Centers the text horizontally within the paragraph */
  vertical-align: middle; /* Aligns the paragraph vertically in its containing element */
  }
  
  .mid{
  max-width: 52ch;
  flex-wrap: wrap;
  line-height: 1.5;
  margin-left:155px;
  padding: 1em;
  text-align: center; /* Centers the text horizontally within the paragraph */
  vertical-align: middle; /* Aligns the paragraph vertically in its containing element */
  
  }
  
  
  a {
  display: inline-block;
  padding: 1em 3.5em;
  background-color: #333;
  color: white;
  text-decoration: none;
  text-transform: uppercase;
  border-radius: 0.3em;
  font-weight: 700;
  letter-spacing: .5px;
  font-size: .875rem;
  }
  
  .blank,
  .other {
  width: 100%;
  min-height: 60vh;
  background-color:#333;
  }
  
  .blanks{
  background-color: rgb(175,148,83);
  }
  
  
  .second {
  background-image:url(https://i.ibb.co/tPv85zH/frontImg.jpg);
  background-attachment: fixed;
  /* height: 1200px; */
  background-size: cover;
  background-position: center;
  }
  
  h3 {
  font-weight: 700;
  font-size: 1.6rem;
  margin-top: 1em;
  }
  
  .card > a {
  margin-bottom: 2em;
  
  }
  .card{
      background: rgb(26, 25, 25,0.45);
      color: white;
  }
  
  .item {
  display: flex;
  max-width: 320px;
  background: rgb(26, 25, 25,0.45);
  flex-direction: column;
  align-items: center;
  border-radius: .5em;
  -webkit-box-shadow: 0px 29px 38px -15px rgba(0,0,0,0.43);
  -moz-box-shadow: 0px 29px 38px -15px rgba(0,0,0,0.43);
  box-shadow: 0px 29px 38px -15px rgba(0,0,0,0.43);
  }
  
  .img {
  width: 90%;
  height: 200px;
  background-color: rgb(225, 225, 225,0.25);
  background-size: cover;
  background-position: center;
  margin-top: 20px;
  border-radius: .3em;;
  }
  
  /* .img-first {
  background-image: url(https://images.unsplash.com/photo-1522163182402-834f871fd851?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1606&q=80);
  } */
  
  .img-second {
  background-image: url(https://images.unsplash.com/photo-1628746404106-4d3843b231b3?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8NHx8Y2F2aW5nfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=900&q=60);
  }
  
  .img-third {
  background-image: url(https://images.unsplash.com/photo-1632853073412-782bf0279d65?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80);
  }
  
  .second {
  flex-direction: row;
  gap: 1.6em;
  }
  
  .box{
  background: rgb(26, 25, 25,0.45);
  padding: 65px;
  padding-left: 85px;
  padding-right: 85px;
  border-radius:25px;
  
  }
  
  /* testimonials */
  .heading {
  text-align: center;
  color: #454343;
  font-size: 30px;
  font-weight: 700;
  position: relative;
  margin-bottom: 70px;
  text-transform: uppercase;
  z-index: 999;
  }
  .white-heading{
  color: #ffffff;
  }
  .heading:after {
  content: ' ';
  position: absolute;
  top: 100%;
  left: 50%;
  height: 40px;
  width: 180px;
  border-radius: 4px;
  transform: translateX(-50%);
  /* background: url(img/heading-line.png); */
  background-repeat: no-repeat;
  background-position: center;
  }
  .white-heading:after {
  background: url(https://i.ibb.co/d7tSD1R/heading-line-white.png);
  background-repeat: no-repeat;
  background-position: center;
  }
  
  .heading span {
  font-size: 18px;
  display: block;
  font-weight: 500;
  }
  .white-heading span {
  color: #ffffff;
  }
  /*-----Testimonial-------*/
  
  .testimonial:after {
  position: absolute;
  top: -0 !important;
  left: 0;
  content: " ";
  /* background: url(img/testimonial.bg-top.png); */
  background-size: 100% 100px;
  width: 100%;
  height: 100px;
  float: left;
  z-index: 99;
  }
  
  .testimonial {
  min-height: 375px;
  position: relative;
  /* background: url(https://i.ibb.co/PTJDkgb/testimonials.jpg); */
  padding-top: 50px;
  padding-bottom: 50px;
  background-position: center;
      background-size: cover;
  }
  #testimonial4 .carousel-inner:hover{
  cursor: -moz-grab;
  cursor: -webkit-grab;
  }
  #testimonial4 .carousel-inner:active{
  cursor: -moz-grabbing;
  cursor: -webkit-grabbing;
  }
  #testimonial4 .carousel-inner .item{
  overflow: hidden;
  }
  
  .testimonial4_indicators .carousel-indicators{
  left: 0;
  margin: 0;
  width: 100%;
  font-size: 0;
  height: 20px;
  bottom: 15px;
  padding: 0 5px;
  cursor: e-resize;
  overflow-x: auto;
  overflow-y: hidden;
  position: absolute;
  text-align: center;
  white-space: nowrap;
  }
  .testimonial4_indicators .carousel-indicators li{
  padding: 0;
  width: 14px;
  height: 14px;
  border: none;
  text-indent: 0;
  margin: 2px 3px;
  cursor: pointer;
  display: inline-block;
  background: #ffffff;
  -webkit-border-radius: 100%;
  border-radius: 100%;
  }
  .testimonial4_indicators .carousel-indicators .active{
  padding: 0;
  width: 14px;
  height: 14px;
  border: none;
  margin: 2px 3px;
  background-color: #9dd3af;
  -webkit-border-radius: 100%;
  border-radius: 100%;
  }
  .testimonial4_indicators .carousel-indicators::-webkit-scrollbar{
  height: 3px;
  }
  .testimonial4_indicators .carousel-indicators::-webkit-scrollbar-thumb{
  background: #eeeeee;
  -webkit-border-radius: 0;
  border-radius: 0;
  }
  
  .testimonial4_control_button .carousel-control{
  top: 175px;
  opacity: 1;
  width: 40px;
  bottom: auto;
  height: 40px;
  font-size: 10px;
  cursor: pointer;
  font-weight: 700;
  overflow: hidden;
  line-height: 38px;
  text-shadow: none;
  text-align: center;
  position: absolute;
  background: transparent;
  border: 2px solid #ffffff;
  text-transform: uppercase;
  -webkit-border-radius: 100%;
  border-radius: 100%;
  -webkit-box-shadow: none;
  box-shadow: none;
  -webkit-transition: all 0.6s cubic-bezier(0.3,1,0,1);
  transition: all 0.6s cubic-bezier(0.3,1,0,1);
  }
  .testimonial4_control_button .carousel-control.left{
  left: 7%;
  top: 50%;
  right: auto;
  }
  .testimonial4_control_button .carousel-control.right{
  right: 7%;
  top: 50%;
  left: auto;
  }
  .testimonial4_control_button .carousel-control.left:hover,
  .testimonial4_control_button .carousel-control.right:hover{
  color: #000;
  background: #fff;
  border: 2px solid #fff;
  }
  
  .testimonial4_header{
  top: 0;
  left: 0;
  bottom: 0;
  width: 550px;
  display: block;
  margin: 30px auto;
  text-align: center;
  position: relative;
  }
  .testimonial4_header h4{
  color: #ffffff;
  font-size: 30px;
  font-weight: 600;
  position: relative;
  letter-spacing: 1px;
  text-transform: uppercase;
  }
  
  .testimonial4_slide{
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  width: 70%;
  margin: auto;
  padding: 20px;
  position: relative;
  text-align: center;
  }
  .testimonial4_slide img {
  top: 0;
  left: 0;
  right: 0;
  width: 136px;
  height: 136px;
  margin: auto;
  display: block;
  color: #f2f2f2;
  font-size: 18px;
  line-height: 46px;
  text-align: center;
  position: relative;
  border-radius: 50%;
  box-shadow: -6px 6px 6px rgba(0, 0, 0, 0.23);
  -moz-box-shadow: -6px 6px 6px rgba(0, 0, 0, 0.23);
  -o-box-shadow: -6px 6px 6px rgba(0, 0, 0, 0.23);
  -webkit-box-shadow: -6px 6px 6px rgba(0, 0, 0, 0.23);
  }
  .testimonial4_slide p {
  color: #ffffff;
  font-size: 20px;
  line-height: 1.4;
  margin: 40px 0 20px 0;
  }
  .testimonial4_slide h4 {
  color: #ffffff;
  font-size: 22px;
  }
  
  .testimonial .carousel {
  padding-bottom:50px;
  }
  .testimonial .carousel-control-next-icon, .testimonial .carousel-control-prev-icon {
  width: 35px;
  height: 35px;
  }
  /* ------testimonial  close-------*/
  </style>