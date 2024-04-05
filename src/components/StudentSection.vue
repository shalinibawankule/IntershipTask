<template>
    <section class="products" id="product1">
        <h2 class="heading">Preskilet for Students</h2>

        <div id="container1" class="product-container">
            <div id="student-box1" class="product-box">
                <i class="fas fa-user"></i>
                <h3>Profile</h3>
                <p>Profile is one of the most important part of the Preskilet Profile. Make sure you enter corrent information, because if any recruiter likes your Profile, he will try to contact you based on your contact information.</p>
            </div>

            <div id="student-box2" class="product-box">
                <i class="fas fa-search"></i>
                <h3>Search</h3>
                <p>Search people by names with the help of preskilet.</p>
            </div>

            <div id="student-box3" class="product-box">
                <i class="fas fa-video"></i>
                <h3>Video</h3>
                <p>Using Video section you can upload your videos.In Edit videos section you can edit or delete your previosly uploaded videos.</p>
            </div>
            
        </div>
    </section>


</template>




<script>
export default {
  
}

</script>





<style>

#product1 .heading{
    text-align: center;
    font-size:3rem;
    padding-top: 100px;
   
}
#product1{
    width: 100%;
    background-color:rgb(226, 226, 226);
}
.product-container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    gap: 20px;
    padding:70px;
    
}

.product-box {
    flex: 1 1 5rem;
    background: white;
    padding: 3rem 2rem 2rem;
    border-radius: 2rem;
    text-align: center;
    border: 0.2rem solid #0a66c2;
    transition: .5s ease;
}




.product-box:hover{
   border-color: black;
   transform: scale(1.02);
 }
 .product-box i{
   font-size: 3rem;
   color: #0a66c2;
 }
 .product-box h3{
   font-size: 2rem;
 }
 .product-box p{
   font-size: 1.2rem;
   margin: 1rem 0 3rem;
 }
</style>
