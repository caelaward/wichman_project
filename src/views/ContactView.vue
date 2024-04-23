<template>
   <div class="container">
    <div class="row">
        <div class="col-lg-6">
           <div class="txt">
            <h1>
                Contact us to turn your dream into a reality.
            </h1>
           </div>

        </div>
        <div class="col-lg-6">
            <div class="form">
    <h2>Please fill out this form and we will get back to you shortly</h2>
    <form>
        <div class="form-group">
            <input type="text" class="form-control" placeholder="Name">
            <input type="text" class="form-control" placeholder="Subject">
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
</template>



<style scoped>
.txt{
    width: 350px;
    height: 500px;
    background-color:  rgb(175,148,83);
    justify-content: center;
    display: flex;
    align-items: center;
}
.form {
    display: flex; /* Use flexbox layout */
    flex-direction: column; /* Arrange items vertically */
    justify-content: center; /* Align items along the vertical axis (centering vertically) */
    align-items: center; /* Align items along the horizontal axis (centering horizontally) */
}


.form-group {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    margin-bottom: 10px; /* Adjust margin as needed */
}

.form-group input {
    flex: 1; /* Take up available space */
    margin-right: 10px; /* Adjust spacing between inputs */
 
}
.form-control{
    border-top: none; /* Remove top border */
    border-left: none; /* Remove left border */
    border-right: none; /* Remove right border */
    border-radius: 0; /* Ensure no border radius */
    transition: border-color 0.3s; 
}

.form-group input:last-child {
    margin-right: 0; /* Remove margin from the last input to prevent extra space */
}

.form-control:hover {
    border-color: #000; /* Set border color on hover */
}
h1{
    color: white;
    font-size: 30px;
    line-height: 55px;
}

.btn {
    border-top: none; /* Remove top border */
    border-left: none; /* Remove left border */
    border-right: none; /* Remove right border */
    border-radius: 0; /* Ensure no border radius */
    transition: border-color 0.3s; 
    background: transparent;
    color: rgb(175,148,83);
    border-bottom: 2px solid rgb(175,148,83); /* Set bottom border */
}

.btn:hover {
    border-color: transparent; /* Remove bottom border on hover */
}




</style>