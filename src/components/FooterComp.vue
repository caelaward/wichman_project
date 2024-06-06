<template>
    <div class="d-flex flex-column h-100">


    <!-- FOOTER -->
    <footer class="w-100 py-4 flex-shrink-0 ">
        <div class="container py-4">
            <div class="row gy-4 gx-5">
                <div class="col-lg-4 col-md-6">
                    <h5 class="h1 text-black"> W&C</h5>
                    <p class="small text-white"> <p>71 Allenby Drive, Retreat,</p>
                <p>Cape Town, South Africa 7945</p>
               </p>
                    <p class="small text-white mb-0">&copy; Copyrights. All rights reserved.<a class="text-primary" href="#">Wichman & Co Event Planning</a></p>
                </div>
                <div class="col-lg-2 col-md-6">
                    <h5 class="text-black mb-3">Quick links</h5>
                    <ul class="list-unstyled text-muted">
                        <li><router-link to="/about" @click="scrollToTop()">About</router-link></li>
                        <li><router-link to="/service" @click="scrollToTop()">Service</router-link></li>
                        <li><router-link to="/projects" @click="scrollToTop()">Our work</router-link></li>
                        <li><router-link to="/contact" @click="scrollToTop()">Conact</router-link></li>
                    </ul>
                </div>
                <div class="col-lg-2 col-md-6">
                    <h5 class="text-black  mb-3">Get in touch</h5>
                    <ul class="list-unstyled text-muted">
                        <li><a href="#"><i class="fa-brands fa-instagram"></i></a></li>
                        <li><a href="#"><i class="fa-brands fa-square-facebook"></i></a></li>
                        <li><a href="#"><i class="fa-solid fa-envelope-circle-check"></i></a></li>
                        <li><a href="#"><i class="fa-solid fa-square-phone"></i></a></li>
                    </ul>
                </div>
                <div class="col-lg-4 col-md-6">
                    <h5 class="text-black mb-3">Chat box</h5>
                    <p class="small text-white">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt.</p>
                    <form action="#">
                        <div class="input-group mb-3">
                            <input class="form-control" type="text" placeholder="Recipient's username" aria-label="Recipient's username" aria-describedby="button-addon2">
                            <button class="btn btn-primary" id="button-addon2" type="button"><i class="fas fa-paper-plane"></i></button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </footer>
</div>
</template>

<script>
export default {
    methods: {
    scrollToTop() {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    }
  }
}
</script>

<style scoped>

footer{
    margin-top:1%;
    background-color: rgb(175,148,83);
    
}

div{
   
    background-color:  rgb(175,148,83);
}

.text-small {
  font-size: 0.9rem;
 
}

a {
  color: white;
  text-decoration: none;
  transition: all 0.3s;
}

a:hover, a:focus {
  text-decoration: none;
}

.form-control {
  background: #212529;
  border-color: #545454;
}

.form-control:focus {
  background: #212529;
}



/* ==========================================
    CUSTOM UTILS CLASSES
  ========================================== */
 
</style>