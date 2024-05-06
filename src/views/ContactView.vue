<template>
   <div class="container  mx-auto">
    <div class="row">
        <div class="col-lg-6">
           <div class="txt">
            <h1>
                Contact us to turn your dream into a reality.
            </h1>
           </div>

        </div>
        <div class="col-lg-6 mt-5">
            <div class="form">
    <h2>Please fill out this form and we will get back to you shortly</h2>
    <form>
        <div class="form-group">
            <input type="text" class="form-control" placeholder="Name">
            <input type="text" class="form-control" placeholder="Phone number">
        </div>
        <div class="form-group">
            <input type="email" class="form-control" placeholder="Email">
        </div>
        <div class="form-group">
            <textarea class="form-control" placeholder="Message"></textarea>
        </div>
        <input type="submit" class="btn">
    </form>
</div>

        </div>
    </div>
   </div>

   <div class="container mx-auto">
    <div class="row">
        <div class="col-lg-6">
            <div class="text-section">
                <h1 class="text-dark">
                    WICHMAN & CO EVENT PLANNING
                </h1>
                <p>71 Allenby Drive, Retreat,</p>
                <p>Cape Town, South Africa 7945</p>
                <p>Cell: +27 71 864 5141</p>
                <p>Home: +27 21 701 1734</p>
                <p>Email: info@wichmanandco.co.za</p>
            </div>
        </div>
        <div class="col-lg-6">
            <img src="https://cdn-thumbs.imagevenue.com/da/ce/7a/ME185QRK_b.jpg" alt="">
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
/* Additional styling */
.container {
    padding-top: 50px;
    padding-bottom: 50px;
}

.txt h1 {
    color: white;
    font-size: 30px;
    line-height: 40px;
    text-align: center;
}

.txt{
    width: 350px;
    height: 500px;
    background-color:  rgb(175,148,83);
   display: flex;
   justify-content: center;
   align-items: center;
}

.form h2 {
    color:  rgb(155,128,63);
    font-size: 24px;
    text-align: center;
    margin-bottom: 20px;
}

.form-control {
    border: 1px solid #ccc;
    border-radius: 5px;
    padding: 10px;
    width: 100%;
    margin-bottom: 15px;
    border-top: none; /* Remove top border */
    border-left: none; /* Remove left border */
    border-right: none; /* Remove right border */
    border-radius: 0;
}
.form-group input:last-child {
    margin-right: 0; /* Remove margin from the last input to prevent extra space */
}

.btn {
    border: none;
    border-radius: 5px;
    background-color: rgb(175,148,83);
    color: white;
    padding: 10px 20px;
    font-size: 18px;
    cursor: pointer;
   
}

.btn:hover {
    background-color: rgb(155,128,63);
}

.text-dark {
    color: #333;
    font-size: 24px;
    margin-bottom: 15px;
}

img {
    max-width: 100%;
    height: auto;
    margin-left: 250px;
}
.text-section {
    padding-right: 20px;
}

.text-section p {
    margin-bottom: 10px;
}

</style>