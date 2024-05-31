<template>
    <div class="mt-4">
        <h1>WEDDINGS</h1>
         <div class="container">
            <div class="row">
                <div class="col-lg-4">
                    <div class="box">
                       <img src="https://cdn-thumbs.imagevenue.com/da/ce/7a/ME185QRK_b.jpg" id="img" alt="">
                      <h2 class="mt-2">Full Package</h2>
                      <p>This service includes everything related to arranging your wedding. From start to finish, we will be by your side, helping you plan your perfect day.</p>
                    </div>
                </div>
                <div class="col-lg-4">
                    <div class="box2">
                       <img src="https://cdn-thumbs.imagevenue.com/da/ce/7a/ME185QRK_b.jpg" id="img" alt="">
                      <h2 class="mt-2">Custom Package</h2>
                      <p>This option allows us to consider a unique planning service based on your budget requirements, where we can try to work out a solution that suits your needs.</p>
                    </div>
                </div>
                <div class="col-lg-4">
                    <div class="box3">
                       <img src="https://cdn-thumbs.imagevenue.com/da/ce/7a/ME185QRK_b.jpg" id="img" alt="">
                      <h2 class="mt-2">Wedding Day Coordination</h2>
                      <p>This service includes us taking over all the final arrangements in the 2 weeks leading up to the wedding day – including setting up a schedule for the day, set-up on the day and breakdown thereafter.</p>
                    </div>
                </div>
            </div>
         </div>
        <br>
          <h1>BIRTHDAY <br>
        CELEBRATIONS</h1>

        <div class="container">
            <div class="row">
                <div class="col-lg-6 d-flex justify-content-between">
                    <div class="box4">
                       <img src="https://cdn-thumbs.imagevenue.com/da/ce/7a/ME185QRK_b.jpg" alt="">
                      <h2 class="mt-2">Kid's Birthdays</h2>
                      <p>From Cat in the Hat to Minnie Mouse, whatever theme your child loves, we can create custom party packs, candy tables, backdrops and so much more to bring their favourite characters to life. .</p>
                    </div>
                </div>
                <div class="col-lg-6 d-flex justify-content-between">
                    <div class="box5">
                       <img src="https://cdn-thumbs.imagevenue.com/da/ce/7a/ME185QRK_b.jpg" alt="">
                      <h2 class="mt-2">Adult Birthdays</h2>
                      <p>We offer decor solutions that suit your sophisticated or festive needs. We also offer catering, service staff and bartender services to make sure you and your guests enjoy your special day.</p>
                    </div>
                </div>
            </div>
         </div>
         <br>
         <h1>CORPORATE EVENTS</h1>
        <div class="container">
            <div class="row">
                <div class="col-lg-6 d-flex justify-content-between">
                    <div class="box4">
                       <img src="https://cdn-thumbs.imagevenue.com/da/ce/7a/ME185QRK_b.jpg" alt="">
                      <h2 class="mt-2">Activations</h2>
                      <p>Large-scale activations that require custom-styled promoters, decor for multiple spaces, service staff, catering, corporate gifting and talent such as magicians or jugglers, whatever your business needs, we can do it!</p>
                    </div>
                </div>
                <div class="col-lg-6 d-flex justify-content-between">
                    <div class="box5">
                       <img src="https://cdn-thumbs.imagevenue.com/da/ce/7a/ME185QRK_b.jpg" alt="">
                      <h2 class="mt-2">Corporate Parties</h2>
                      <p>From year-end functions to product or service launches, we can create a memorable corporate event for you and your team.</p>
                    </div>
                </div>
            </div>
         </div>
         <br>
         <h1>CATERING</h1>
         <div class="box6">
            <img src="https://cdn-thumbs.imagevenue.com/da/ce/7a/ME185QRK_b.jpg" alt="">
            <h2 class="mt-2">Feast Your Eyes</h2>
                      <p>From set courses, buffets to canapes, Trust our catering team to tantalise the palettes of you and your guests at your wedding, birthday celebration, private or corporate events.</p>
         </div>
         <br>
         <h1>STAFF</h1>
         <div class="box7">
            <img src="https://cdn-thumbs.imagevenue.com/da/ce/7a/ME185QRK_b.jpg" alt="">
            <h2 class="mt-2">W&C Team</h2>
                      <p>We have a team of friendly and well-trained floor managers, waitresses, waiters, bartenders and porters. Our team is rich in cultures and nationalities and they provide the human element to our brand.</p>
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
.box,.box2,.box3{
    width: 350px;
    height: 500px;
    background-color: rgba(217, 217, 217, 0.15);
    text-align: center;
    padding: 2.5px;
    /* display: flex; */
    /* flex-direction: column; */

}
img{
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-top: 40px;
}
#img{
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-top: 40px;
    margin-left: 2.5px;
}
.box4, .box5 {
   /* position: relative; */
   background-color: rgba(217, 217, 217, 0.15);
        width: 800px;
        height: 640px;
        text-align: center;
        margin-bottom: 35px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;

}
.box6,.box7{
    background-color: rgba(217, 217, 217, 0.15);
    height: 400px;
    margin-bottom: 35px;
    text-align: center;
    display: flex;
    justify-content: center;
        align-items: center;
        flex-direction: column;
}
h1{
    color: rgb(175,148,83) !important;
    letter-spacing: 0.45em !important;
}
h2{
    color: rgb(175,148,83) !important;
    letter-spacing: 0.2em !important;
}
p{
    max-width: 52ch;
    padding: 1em;
}

</style>