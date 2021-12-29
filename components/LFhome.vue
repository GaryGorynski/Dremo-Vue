<template>
<div>
   <section class="lfhome">
        <h1 class="lfhome__heading">Are you looking for <br><span class="lfhome__heading-span">dream </span>home?</h1>
          <p class="lfhome__paragraph"> The most accurate property valuation Website in<span class="lfhome__paragraph-span">Sylhet</span></p>
          <div class="lfhome__imgbox">
            <img class="lfhome__imgboxImg" src="/assets/sofatest.png" alt="hero image">
           </div>
            <div class="select">
             <ul class="select__list"> 
              <li>
               <a class="select__location" href="#">Location <span class="arrow"></span></a>
              </li>
              <li>
               <a class="select__property" href="#">Property type<span class="arrow"></span></a>
              </li>
              <li>
               <a class="select__price nthh" href="#">Max price<span class="arrow"></span></a>
              </li>
             </ul>
              <ul class="select__data">
               <li>
                <a href="">Sylhet</a>
               </li>
               <li>
                <a href="">Duplex</a>
               </li>
               <li>
                <a href="" class="nth">$3,000</a>
               </li>
               </ul>        
               <button class= "select__btn" id="butt">
                <i class="select__search fa fa-search"></i>
               </button>
            </div>  
    </section>
    </div>
</template>

<script>
export default {
    name: 'LFhome'

}
</script>

<style>
.lfhome__heading {
    font-family: Poppins;
    font-style: normal;
    font-weight: 500;
    font-size: 64px;
    text-align: center;
    text-align-last: center;
    justify-content: center;
    line-height: 80px;
    padding-top: 45px;
       
}
.lfhome__heading-span {
    color: #4270C9;
}
.lfhome__paragraph {
    font-family: 'Poppins';
    font-style: normal;
    font-size: 24px;
    font-weight:300;
    color: #656565;
    text-align: center;   
    margin-top: 51px;
    line-height: 15%;

}
.lfhome__paragraph-span {
    font-family: 'Poppins';
    font-style: normal;   
    font-weight: 300;
        font-size: 24px;
        padding-left: 6px;
        display:inline-block;
        border-bottom:0.06em solid black;
        padding-bottom:8px;
}
.lfhome__imgbox {
    
    width: 1519px;
    height: 640px;
    margin-top: 50px;
    background-color: red;
    
 }
 .lfhome__imgboxImg {
    width: 100%;
    height: 100%;
}

.select {
    position: relative;
    top: -50px;
    left: 375px;
width: 768px;
height: 108px;
background: white;
box-shadow: 0px 4px 100px rgba(0, 0, 0, 0.15);
border-radius: 60px;
}

.select__list {
    display: flex;
    justify-content: space-around;
    width: 75%; 
     padding-top: 5%;
    font-family: 'Poppins';
    font-style:normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 15px;
    color: #000000;
}
.select__list li {
    list-style: none;
}
.select__list a {
    color: black;
    text-decoration: none;
    
}
.arrow {
    
    border: solid black;
    border-width: 0 3px 3px 0;
    display: inline-block;
    padding: 3px;
    margin-left: 20px;
    margin-bottom: 3px;   
    transform: rotate(45deg);
    -webkit-transform: rotate(45deg);
  }
  
  .select__data {
    display: flex;
    justify-content:space-between;
    width: 52%;
    margin-left: 35px;
    line-height: 15px;
    font-family: Poppins;
    font-style:normal;
    font-weight: 500;
    font-size: 14px;
    padding-right: 100px;
    
}
.select__data li {
    list-style: none;
}
.select__data a {
    text-decoration: none;
    color: rgba(0, 0, 0, 0.5);
}
.nthh {
    margin-right: 40px;
}
.nth {
    margin-left: 23%;
} 

.select__btn {
    width: 54px;
    height: 54px;
    background-color: #4270c9;
    border-radius: 10px;
    border-style: none;
    float: right;
    position: relative;
    right: 65px;
    bottom: 70px;
    
    
}
.select__search {
    color: white;
    font-size: 33px;
    
}
.select__btn:hover{
    background-color: white;
    transition: 0.3s;
    box-shadow: 4px 20px 32px rgba(158, 175, 201, 0.7);
}
.select__btn:hover .select__search{
    transition: 0.3s;
    color:#4270c9;;

}

</style>