<template>
   <section class="booking">
        <h3 class="booking__head">The safest way to book your land/home</h3>
          <p class="booking__p1">Get your home booked quickly and recive the first payment through our platfrom. We’ll protect you against last-minute surprises. identifiers, how they weighted and the power   to use powerful technology change it.</p>
            <p class="booking__p2">Manage all your enquires and booking requests from one placel and syntax that you are familier with,so you can get productive We quickly now.</p>
             <div class="booking__imgs">
               <img class="booking__imgsmall" src="/assets/maly.png" alt="noimg">
                 <img class="booking__imglarge" src="/assets/duze.png" alt="noimg">
                   <div class="booking__elipse">
                     <span class="booking__elipse-span"></span>
                   </div>
             </div>
                     <button class="booking__btn">
                       <span class="booking__btn-txt">Book Now</span>
                        <i class="fas fa-arrow-right booking__btn-hover"></i>
                     </button>              
      </section>
</template>

<script>
export default {
name:'Booking'
}
</script>

<style>
 .booking {
        position: absolute;
    width: 1303px;
    height: 622px;
    left: 137px;
    top: 2164px;
    
    }
    .booking__head {
    position: relative;
    width: 465px;
    height: 120px;
    margin-left: 25px;
    top: 20px;
    font-family: Poppins;
    font-style: normal;
    font-weight: 500;
    font-size: 40px;
    line-height: 149%;
    letter-spacing: 0.030em;
    color: #000000;
    }
    .booking__p1 {
    width: 520px;
    height: 108px;
    margin-left: 25px;
    font-family: Poppins;
    font-style: normal;
    font-weight:500;
    font-size: 16px;
    line-height: 171%;
    letter-spacing: 0.025em;
    color: #000000;
    }
    
    .booking__p2 {

        width: 550px;
        height: 81px; 
        margin-left: 25px;   
        font-family: Poppins;
        font-style: normal;
        font-weight: 500;
        font-size: 16px;
        line-height: 27px;
        
        letter-spacing: 0.025em;
        
        color: #000000;
    }
    .booking__imgs {
        width: 815px;
        height: 622px;
        margin-left: 510px;
        margin-top: -400px;
        overflow:visible;
        filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
        
    }
    .booking__imglarge    {
        margin-left: 161px;
        margin-top: -0px;
    border-radius: 5px;   
    }
    .booking__imgsmall {
        position: absolute;
    filter: drop-shadow(0px 4px 100px #CAC8C8);
    border-radius: 5px;
    margin-top: 408px;
    z-index: 1;
    }
    .booking__elipse {
        position: absolute;
        width: 424px;
        height: 373px;
        left: 295px;
        top:85px;
        
    }
    .booking__elipse-span {
        position: absolute;
        width: 424px;
        height: 373px;
        background: rgba(255, 255, 255, 0.5);
        border: 1px dashed #FFFEFE;
        border-width: 4px;
    
        box-sizing: border-box;
        border-radius: 61% 65% 23% 62% / 59% 100% 23% 56% ;
    }
    
    
    .booking__btn {
        position: relative;
    height: 75px;
    width: 210px;
    bottom:170px;
    left: 20px;
    background: #4270C9;  
    color: white;
    border-radius: 60px;
    border-style: ridge;
    border:none;
    }
    .booking__btn-txt {
     position: relative;
     font-family: Poppins;
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    bottom: 5px;
    left: 8px;
}
    
    .booking__btn-hover {
        color: #4270c9;
        background-color: white;
        font-size: 26px;
        font-weight: 600;
        margin-left: 25px;
        margin-top: 1px;
        border-style:solid;
        border-radius: 40px 40px;
        border-width: 15px;
        border-color: white;

    }
    .booking__btn:hover{
        background: white;
        color: #4270c9;
        transition: 0.3s;
        box-shadow: 4px 20px 32px rgba(158, 175, 201, 0.7);
    }
    .booking__btn:hover .booking__btn-hover{
        transition: 0.3s;
        color:white;
        border-color: #4270c9;
        background-color: #4270c9;
    }
</style>