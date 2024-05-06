<template>
    <div class="mt-4">
        <h1>WEDDINGS</h1>
         <div class="container">
            <div class="row">
                <div class="col-lg-4">
                    <div class="box">
                       <img src="https://cdn-thumbs.imagevenue.com/da/ce/7a/ME185QRK_b.jpg" id="img" alt="">
                      <h1 class="mt-2">Title</h1>
                      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi voluptas quae perferendis sunt assumenda incidunt modi quam libero adipisci sequi. Iusto quo sequi aut, laudantium modi possimus ullam reiciendis obcaecati.</p>
                    </div>
                </div>
                <div class="col-lg-4">
                    <div class="box2">
                       <img src="https://cdn-thumbs.imagevenue.com/da/ce/7a/ME185QRK_b.jpg" id="img" alt="">
                      <h1 class="mt-2">Title</h1>
                      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi voluptas quae perferendis sunt assumenda incidunt modi quam libero adipisci sequi. Iusto quo sequi aut, laudantium modi possimus ullam reiciendis obcaecati.</p>
                    </div>
                </div>
                <div class="col-lg-4">
                    <div class="box3">
                       <img src="https://cdn-thumbs.imagevenue.com/da/ce/7a/ME185QRK_b.jpg" id="img" alt="">
                      <h1 class="mt-2">Title</h1>
                      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi voluptas quae perferendis sunt assumenda incidunt modi quam libero adipisci sequi. Iusto quo sequi aut, laudantium modi possimus ullam reiciendis obcaecati.</p>
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
                      <h1 class="mt-2">Title</h1>
                      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi voluptas quae perferendis sunt assumenda incidunt modi quam libero adipisci sequi. Iusto quo sequi aut, laudantium modi possimus ullam reiciendis obcaecati.</p>
                    </div>
                </div>
                <div class="col-lg-6 d-flex justify-content-between">
                    <div class="box5">
                       <img src="https://cdn-thumbs.imagevenue.com/da/ce/7a/ME185QRK_b.jpg" alt="">
                      <h1 class="mt-2">Title</h1>
                      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi voluptas quae perferendis sunt assumenda incidunt modi quam libero adipisci sequi. Iusto quo sequi aut, laudantium modi possimus ullam reiciendis obcaecati.</p>
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
                      <h1 class="mt-2">Title</h1>
                      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi voluptas quae perferendis sunt assumenda incidunt modi quam libero adipisci sequi. Iusto quo sequi aut, laudantium modi possimus ullam reiciendis obcaecati.</p>
                    </div>
                </div>
                <div class="col-lg-6 d-flex justify-content-between">
                    <div class="box5">
                       <img src="https://cdn-thumbs.imagevenue.com/da/ce/7a/ME185QRK_b.jpg" alt="">
                      <h1 class="mt-2">Title</h1>
                      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi voluptas quae perferendis sunt assumenda incidunt modi quam libero adipisci sequi. Iusto quo sequi aut, laudantium modi possimus ullam reiciendis obcaecati.</p>
                    </div>
                </div>
            </div>
         </div>
         <br>
         <h1>CATERING</h1>
         <div class="box6">
            <img src="https://cdn-thumbs.imagevenue.com/da/ce/7a/ME185QRK_b.jpg" alt="">
            <h1 class="mt-2">Title</h1>
                      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi voluptas quae perferendis sunt assumenda incidunt modi quam libero adipisci sequi. Iusto quo sequi aut, laudantium modi possimus ullam reiciendis obcaecati.</p>
         </div>
         <br>
         <h1>STAFF</h1>
         <div class="box7">
            <img src="https://cdn-thumbs.imagevenue.com/da/ce/7a/ME185QRK_b.jpg" alt="">
            <h1 class="mt-2">Title</h1>
                      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi voluptas quae perferendis sunt assumenda incidunt modi quam libero adipisci sequi. Iusto quo sequi aut, laudantium modi possimus ullam reiciendis obcaecati.</p>
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
p{
    max-width: 52ch;
    padding: 1em;
}

</style>