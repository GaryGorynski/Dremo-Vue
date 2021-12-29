<template>
  <section class="how">
        <div class="how">
         <h2 class="how__title">How it works</h2>
          <p class="how__subtitle">Safe and easy! Your booking will be confirmed in less than 2 working<br> days stop the flat visits and welcome the right person</p>
        </div>
         <div class="how__search">
          <img class="how__searchImg" src="/assets/jeden.png" alt="noimg">
           <rect class="how__searchRect"> <span class="how__searchRect-span">01</span></rect>
            <h3 class="how__searchTitle">Search</h3>
             <p class="how__searchText">Find a home from our search bar. Enter your specific location and date</p>
          </div>
           <div class="how__choose">
            <img class="how__chooseImg" src="/assets/dwa.png" alt="noimg">
             <rect class="how__chooseRect"> <span class="how__chooseRect-span">02</span></rect>
              <h3 class="how__chooseTitle">Choose</h3>
               <p class="how__chooseText">Choose your desire home on expected date for your events.</p>
           </div>
             <div class="how__book">
              <img class="how__bookImg" src="/assets/trzy.png" alt="noimg">
               <rect class="how__bookRect"> <span class="how__bookRect-span">03</span></rect>
                <h3 class="how__bookTitle">Book</h3>
                 <p class="how__bookText">Book your desire home<br> expected date for your events.</p>
             </div>               
             <div class="how__lines">  
                <svg class="how__blackline" height="250" width="500">
                 <line x1="0" y1="0" x2="0" y2="100" style="stroke:black;stroke-width:2" />
                </svg>  
                 <svg class="how__whiteline" height="55" width="10">
                  <line x1="0" y1="0" x2="0" y2="200" style="stroke:#F1F1F1;stroke-width:5" />
                 </svg>
                   <p class="how__lineOne">01</p>
                    <p class="how__lineTwo">/03</p>
                   </div>
       </section>
</template>

<script>
export default {
name: 'How-it-works'
}
</script>

<style>
.how__title {
    margin-top: 80px;
    text-align: center;
    margin-left: 20px;
    font-family: poppins;
    font-style: normal;
    font-weight: 400;
    font-size: 40px;
color: #000000;
}

.how__subtitle {
    
justify-content: center;
text-align-last: center;
font-family: Poppins;
font-style: normal;
font-weight: 500;
font-size: 13px;
margin-top: 30px;
margin-left: 20px;
opacity: 0.90;
}
.how__search {
    
    float: left;
    margin-left: 300px;
    width: 16%;
    margin-top: 65px;
    padding-right: 105px;
    
    
}
.how__searchImg {
object-position: right;
border-radius: 5px;
transform: rotate(0.41deg);
}    
.how__searchRect {
position: absolute;   
width: 50px;
height: 53px;
background: #000000;
font-family: 'Poppins';
border-radius: 0px 30px 0px 0px;
margin-top: -57px;
margin-left: -2px;
    }

.how__searchRect-span {
    position: absolute;
    color: white;
    font-size: 25px;
    font-weight: 300;
    margin-left: 10px;
    margin-top: 5px;
    
    

}
.how__searchTitle {
    
font-family: Poppins;
font-style: normal;
font-weight:400;
font-size: 25px;
color: #000000;
line-height: 20px;

}
.how__searchText {
align-items: center;
justify-content: space-around;
width: 250px;    
font-family: Poppins;
font-style: normal;
font-weight: normal;
font-size: 14px;
color: #888888;


}
.how__choose {
       float: left;
    margin-top: 90px;
    width: 20%;
    padding-right: 55px;   
    
}
.how__chooseImg {
 object-position:right;
filter: drop-shadow(0px 16px 24px rgba(112, 144, 176, 0.2));
border-radius: 5px;
}
.how__chooseRect {
   position: absolute;
width: 50px;
height: 53px;
margin-top: 310px;
margin-left: -50px;
background: #4270C9;
border-radius: 30px 0px 0px 0px;
}
.how__chooseRect-span {
   color: white;
   font-family: 'Poppins';
   font-weight: 300;
   font-size: 25px;
   position: relative;
   left: 10px;
   top: 10px;
}
.how__chooseTitle {

    font-family: Poppins;
    font-style: normal;
    font-weight:400;
    font-size: 25px;
    line-height: 20px;
    color: #000000;
    }

    .how__chooseText {
    display: flex;
    font-family: Poppins;
    font-style: normal;
    font-weight: normal;
    width: 250px;
    font-size: 14px;
    line-height: 146.19%;
    color: #7B7878;
    }
    .how__book {
        
        float: left;
        width: 20%;
        margin-top: 70px;
    }
    .how__bookImg {
    border-radius: 5px;
    }
    .how__bookRect {
        position: absolute;
    width: 50px;
    height: 53px;
    margin-top: 305px;
    margin-left: -264px;
    background: #000000;
    border-radius: 0px 30px 0px 0px;
    }
    .how__bookRect-span {
       color: white;
       font-size: 25px;
       font-family: 'Poppins';
       font-weight: 300;
       position: relative;
       left: 10px;
       top: 10px;
    }
    .how__bookTitle {
    font-family: Poppins;
    font-style: normal;
    font-weight:400;
    font-size: 25px;
    line-height: 20px;
    color: #000000;
    }

    .how__bookText{
    font-family: Roboto;
    font-style: normal;
    font-weight:normal;
    width: 250px;
    font-size: 14px;
    line-height: 146.19%;
    color: #7B7878;
    }

    .how__lines {
        position: absolute;
        width: 200px;
        height: 200px;
        margin-left: 180px;
        }
    .how__whiteline {
        position: absolute;
        top: 200px;
        left: 11px;
    }
    .how__blackline {
        top: 100px;
        left: 11px;
        position: absolute;
        
    }
    .how__lineOne {
        position: absolute;
        width: 33px;
        height: 14px;
        top: 390px;
    font-family: Poppins;
    font-style: normal;
    font-weight:500;
    font-size: 12px;
    line-height: 114.5%;
    
    color: #000000;
    
    transform: rotate(-89.59deg);
    }
    
    .how__lineTwo {
    position: absolute;
    width: 33px;
    height: 10px;
    top: 380px;
    left: -2px;
    font-family: Poppins;
    font-style: normal;
    font-weight:500;
    font-size: 12px;
    line-height: 114.5%;
    color: #e1cdcd;
    transform: rotate(-89.59deg);
    }
</style>