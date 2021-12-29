<template>
<div>
  <section class="featuredHomes"> 
        <h3 class="featuredHomes__h">Featured Homes</h3>
         <p class="featuredHomes__p">Whether you prefer to live in a fresh and cool environment with like-minded people or need an open space for live in,our Dremo websites visits & booking can be the right fit for you! <br><br>Whether you prefer to live in a fresh and cool environment with like-minded people</p>
          <button class="featuredHomes__btn">
            <span class="featuredHomes__btn-txt">Explore More</span>
             <i class="fas fa-arrow-right featuredHomes__btn-hover"></i>
          </button>       
          <div class="imgBoxOne">
            <img class="imgBoxOne__img" src="/assets/gora1.png" alt="noimg">
             <p class="imgBoxOne__p">2 BHK House 1500 sqft</p>
              <p class="imgBoxOne__p2">Khirki extention</p>
               <p class="imgBoxOne__p3">2 2 <span style="color: #4270C9;">800</span>/month</p>
                <button class="imgBoxOne__btn">See all</button>
                 <i class="imgBoxOne__bed fas fa-bed"></i>
                  <i class="imgBoxOne__bath fas fa-bath"></i>
                   <i class="imgBoxOne__location fas fa-map-marker-alt"></i>
                    <i class="imgBoxOne__dollar fas fa-dollar-sign"></i>
                     <i class="imgBoxOne__circle far fa-circle"></i>
           </div>
            <div class="imgBoxTwo">
             <img class="imgBoxTwo__img" src="/assets/prawo.png" alt="noimg">
              <button class="imgBoxTwo__btn">See all</button>
               <p class="imgBoxTwo__p">3 BHK House 2000 sqft</p>
                <p class="imgBoxTwo__p2"> Supply, Sylhet</p>
                 <p class="imgBoxTwo__p3">2 2 <span style="color: #4270c9;">900</span>/month</p>
                  <i class="imgBoxTwo__bed fas fa-bed"></i>
                   <i class="imgBoxTwo__bath fas fa-bath"></i>
                    <i class="imgBoxTwo__dollar fas fa-dollar-sign"></i>
                     <i class="imgBoxTwo__circle far fa-circle"></i>
                      <i class="imgBoxTwo__location fas fa-map-marker-alt"></i>
            </div>                      
             <div class="imgBoxThree">
              <img class="imgBoxThree__img" src="/assets/lewo.png" alt="noimg">
               <button class="imgBoxThree__btn">See all</button>
                <p class="imgBoxThree__p">2 BHK House 1350 sqft</p>
                 <p class="imgBoxThree__p2">2 2 <span style="color: #4270c9">670</span>/month</p>
                  <p class="imgBoxThree__p3">Housing state</p>
                   <i class="imgBoxThree__bed fas fa-bed"></i>
                    <i class="imgBoxThree__bath fas fa-bath"></i>
                     <i class="imgBoxThree__dollar fas fa-dollar-sign"></i>
                      <i class="imgBoxThree__circle far fa-circle"></i>
                       <i class="imgBoxThree__location fas fa-map-marker-alt"></i>
             </div>  
             <div class="videoBox">
              <img class="videoBox__img" src="/assets/widelo.png" alt="novideo">
               <svg class="videoBox__play">  </svg>
                <svg class="videoBox__dot"></svg>
                 <svg class="videoBox__triangle"></svg>
                  <svg class="videoBox__triangleMini"></svg>
                   <svg class="videBox__rectangle"></svg>
                    <svg class="videBox__rectangle2"></svg>
                     <svg class="videBox__rectangle3"></svg>   
                      <i class="videoBox__volume fas fa-volume-up"></i>
                       <i class="videoBox__settings fas fa-cog"></i>
                        <i class="videoBox__window fas fa-expand"></i>
                         <hr class="videoBox__line">
                          <hr class="videoBox__line2">
                           <p class="videoBox__txt">1:01/6.21</p>
             </div>
             </section>
             </div>
</template>

<script>
export default {
name:'Featured'
}
</script>

<style>
.featuredHomes__h {
        position: relative;
    width: 333px;
    height: 58px;
    margin-top: 1600px;
    margin-left: 870px;
    justify-content: center;
    align-items: center;
    white-space: nowrap;
    font-family: Poppins;
    font-style: normal;
    font-weight: 500;
    font-size: 40px;
    line-height: 146.19%;
    /* or 58px */
    
    
    color: #000000;
    } 
    .featuredHomes__p {
        margin-left: 870px;
    width: 422px;
    height: 120px;
    font-family: Poppins;
    font-weight: 400;
    font-size: 18px;
    line-height: 138.19%;
    /* or 30px */
    
    
    color: #150F0F;
    } 
    /* Przycisk */
    .featuredHomes__btn {
        position: relative;
    height: 75px;
    width: 220px;
    left: 850px;
    top: 120px;
    background: white;  
    color:#4270C9;
    border-radius: 60px;
    border-style:solid;
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 600;
    font-size: 18px;
    border-width: 1px;
    }
    .featuredHomes__btn-txt {
        position:relative;
        left: 15px;
        bottom: 4px;
        opacity: 01;
    }
    .featuredHomes__btn-hover {
        color: white;
        background-color: #4270c9;
        font-size: 26px;
        font-weight: 600;
        margin-left: 25px;
        margin-top: 2px;
        border-style:solid;
        border-radius: 30px;
        border-width: 12px;
        border-color: #4270c9;
    }
    .featuredHomes__btn:hover {
        background-color: #4270c9;
        color: white;
        transition: 0.3s;
    }
    .featuredHomes__btn:hover .featuredHomes__btn-hover {
        transition: 0.3s;
        color:#4270c9;
        border-color: white;
        background-color: white;
    }
      
    .imgBoxOne:hover {
        transform: scale(1.2);
        transition: all .2s ease-in-out; 
    }
    .imgBoxOne {
        position: relative;
    width: 241px;
    height: 287px;
    margin-left: 310px;
    bottom: 320px;
    background: #FFFFFF;
    box-shadow: 0px 4px 100px rgba(0, 0, 0, 0.25);
    border-radius: 10px;
    transform: rotate(0.87deg);
    z-index: 1;
    }
    .imgBoxTwo {
    position: relative;
    width: 242px;
    height: 282px;
    left:475px;
    bottom: 360px;
    background: white;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.05);
    border-radius: 5px;
    transform: rotate(1.08deg);
    }
    
    .imgBoxThree {
    position: relative;
    width: 242px;
    height: 288px;
    left:195px;
    bottom: 670px;
    background: #FFFFFF;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.05);
    border-radius: 5px;
    transform: rotate(-90deg);
    }
    
    .imgBoxThree__img {
        position: absolute;
        top:-30px;
        left: 39px;
        transform: rotate(90deg);
    }
    
    .imgBoxOne__p {
        position: absolute;
    left: 8.84%;
    right: 27.93%;
    top: 65.15%;
    bottom: 24.55%;
    font-family: Poppins;
    font-style: normal;
    font-weight: 600;
    font-size: 15px;
    line-height: 21px;
    color: #000000;
    transform: rotate(0.80deg);
    white-space: nowrap;
    }
    .imgBoxOne__p2 {
        position: absolute;
    left: 16.27%;
    right: 51.91%;
    top: 89.51%;
    bottom: 3.28%;
    font-family: Poppins;
    font-style:normal;
    font-weight: 400;
    font-size: 11px;
    line-height: 15px;
    color: #000000;
    transform: rotate(0.1deg);
    white-space: nowrap;
    }
    .imgBoxOne__btn {
        position: absolute;
        left: 71%;
        top: 90.13%;
        bottom: -0.5%;
        height: 30px;
        width: 70px;
        font-family: Poppins;
        font-style: normal;
        font-weight: 400;
        font-size: 13px;
        line-height: 146.19%;
        color: #FFFFFF;
        background: #4270C9;
        border-radius: 2.5px 2.5px 7px;
        border: #4270C9;
        transform: rotate(0.87deg);
        border-color:currentColor;
    }
    .imgBoxOne__bed {
        position: absolute;
        font-size: 17px;
        top: 230px;
        left: 20px;
        
    }
    .imgBoxOne__location {
        position: absolute;
        font-size: 17px;
        top: 257px;
        left: 20px;
    }
    .imgBoxOne__bath {
        position: absolute;
        font-size: 17px;
        top: 230px;
        left: 85px;
    }
    .imgBoxOne__circle {
        position: absolute;
        font-size: 17px;
        top: 232px;
        left: 150px;
    }
    .imgBoxOne__dollar {
        position: absolute;
        font-size: 11px;
        top: 234.5px;
        left: 155.5px;
        
    }
    .imgBoxOne__p3 {
        position: relative;
        word-spacing: 51px;
        top: 45px;
        font-size: 11px;
        left: 54px;
        font-family: roboto;
        font-weight: 400;
    }
    .imgBoxTwo__btn {
        position: absolute;
        font-family: Poppins;
        font-style: normal;
        font-weight: 400;
        font-size: 13px;
        line-height: 123.19%;
        color: #FFFFFF;
            background: #4270C9;
            border-radius: 2.5px 2.5px 2px;
            border: #4270C9;
            transform: rotate(0.87deg);
            border-color:currentColor;
            top: 250px;
            left: 172px;
            height: 30px;
            width: 70px;
            opacity: 0.9;
            
    }
    .imgBoxTwo__p {
        position: absolute;
        font-size: 14px;
        font-family: poppins;
        font-weight: 600;
        font-style: normal;
        color: black;
        line-height: 21px;
        width: 157px;
        height: 21px;
        transform: rotate(0.5deg);
        top: 180px;
        left: 10px;
        white-space: nowrap;
    }
    .imgBoxTwo__p2 {
        position: relative;
        font-family: roboto;
        font-size: 11px;
        line-height: 12px;
        font-style: normal;
        font-weight: normal;
        transform: rotate(1.08deg);
        width: 61px;
        height: 12px;
        top: 67px;
        left: 30px;
        white-space: nowrap;
    }
    .imgBoxTwo__p3 {
     position: relative;
     word-spacing: 51px;
     font-size: 12px;  
     font-family: roboto;
     font-style: normal;
     font-weight: 400;
     top: 20px; 
     left: 44px;
     bottom: -0.5%;
    }
    .imgBoxTwo__bed {
        position: absolute;
        font-size: 17;
        top: 226px;
        left: 15px;
    }
    .imgBoxTwo__bath {
        position: absolute;
        font-size: 17px;
        top: 224px;
        left: 80px;
    }
    .imgBoxTwo__dollar {
        position: absolute;
        top: 227.5px;
        left: 149.5px;
        font-size: 11px;
    }
    .imgBoxTwo__circle {
        position: absolute;
        top: 224.5px;
        left: 144px;
        font-size: 17px;
    }
    .imgBoxTwo__location {
        position:absolute;
        font-size: 17px;
        top: 249px;
        left: 12px;
    }
    .imgBoxThree__p {
      position: absolute;
      font-family: Poppins;
      font-style: normal;
      font-weight: 600;
      font-size: 14px;
      left: 20px;
      top: 190px;
      
    }
    .imgBoxThree__p2 {
        
        position: absolute;
        word-spacing: 51px;
        font-size: 12px;  
        font-family: roboto;
        font-style: normal;
        font-weight: 400;
        top: 220px; 
        left: 62px;
        bottom: -0.5%;
        white-space: nowrap
    }
    .imgBoxThree__p3 {
        position: relative;
        font-family: roboto;
        font-size: 11px;
        line-height: 12px;
        font-style: normal;
        font-weight: normal;
        transform: rotate(1.08deg);
        width: 61px;
        height: 12px;
        top: 215px;
        left: 30px;
        white-space: nowrap;
    }
    .imgBoxThree__bed {
        position: absolute;
        font-size: 17;
        top: 230px;
        left: 27px;
    }
    .imgBoxThree__bath {
        position: absolute;
        font-size: 17px;
        top: 230px;
        left: 89px;
    }
    .imgBoxThree__dollar {
        position: absolute;
        top: 232.5px;
        left: 149.5px;
        font-size: 11px;
    }
    .imgBoxThree__circle {
        position: absolute;
        top: 230px;
        left: 144px;
        font-size: 17px;
    }
    .imgBoxThree__location {
        position:absolute;
        font-size: 17px;
        top: 256px;
        left: 10px;
    }
    .imgBoxThree__btn {
        position: relative;
    width: 70px;
    height: 31px;
    top: 255.48px;
    left: 185px;
    border: none;
    color: white;
    background: #4270C9;
    border-radius: 2.5px 0px 5px;
    }
    
    .videoBox {
        position: relative;
        bottom: 2050px;
        margin-left: 140px;
        align-items: center;
        justify-content: center;
    } 
     .videoBox__img {
        position: absolute;
        top: 1550px;
        left: 100px;
        border-radius: 5px 5px 0px 0px;
    } 
    
   .videoBox__play {
        position: absolute;
    width: 1034px;
    height: 78px;
    left: 212px;
    top: 4120px;
    
    background: rgba(22, 18, 18, 0.6);
    backdrop-filter: blur(8px);
    z-index: 1;
    font-size: 2;
    top:2008px;
    left: 100px;
    } 
    .videoBox__dot {
        height: 75px;
        width: 75px;
        background: #4270C9;
        display: inline-block;
        border-radius: 50%;
        position: absolute;
        top:1747px; 
        left: 575px;
    }
    .videoBox__triangle {
    position:absolute;
        width: 0;
        height: 0;
        border-top: 15px solid transparent;
        border-left: 25px solid white;
        border-bottom: 15px solid transparent;
        top: 1772px;
        left: 604px;
    }
    .videoBox__triangleMini {
        position:absolute;
        width: 0;
        height: 0;
        border-top: 7px solid transparent;
        border-left: 12.5px solid white;
        border-bottom: 7px solid transparent;
        top: 2041px;
        left: 180px;
        z-index: 1;
    }
    
    .videBox__rectangle {
        width: 4px;
        height: 14px;
        background-color: white;
        position: absolute;
        top: 2041px;
        left: 140px;
        z-index: 1;
    }
    .videBox__rectangle2 {
        width: 4px;
        height: 14px;
        background-color: white;
        position: absolute;
        top: 2041px;
        left: 147px;
        z-index: 1;
    }
    .videBox__rectangle3 {
        width: 4px;
        height: 14px;
        background-color: white;
        position: absolute;
        top: 2041px;
        left: 192px;
        z-index: 1;
    }
    .videoBox__volume {
        position: absolute;
        font-size: 20px;
        top: 2038px;
        left: 237px;
        z-index: 1;
        color: white;
    }
    .videoBox__settings {
        position: absolute;
        font-size: 24px;
        top: 2036px;
        left: 1010px;
        z-index: 1;
        color: white;
    }
    .videoBox__window {
        position: absolute;
        font-size: 25px;
        top: 2035px;
        left: 1066px;
        z-index: 1;
        color: white;
    }
    .videoBox__line {
        border-top: 3px solid rgba(255, 255, 255, 0.5); 
        border-bottom: 3px solid rgba(255, 255, 255, 0.5);
        width: 500px;
        position: absolute;
        top: 2037px;
        z-index: 1;
        left: 470px;
        border-radius:5px ;
        background-color: rgba(255, 255, 255, 0.5);
        
    }
    .videoBox__line2 {
        border-top: 3px solid #4270C9; 
        border-bottom: 3px solid#4270C9;
        width: 200px;
        position: absolute;
        top: 2037px;
        z-index: 1;
        left: 350px;
        border-radius:5px ;
        background-color: rgba(255, 255, 255, 0.5);
        
    }
    .videoBox__txt {
        position: relative;
        top: 2043px;
        left: 278px;
        width: 50px;
        font-size: 12px;
        z-index: 1;
        color: white;
        font-family: roboto;
        font-weight: lighter;
        font-style: normal;
    } 
</style>