<template>
  <footer class="last">
<div class="last__logo">Dre<span class="last__logo-span">mo</span>
<i class="last__logoIg fab fa-instagram"></i>
<i class="last__logoIn fab fa-linkedin-in"></i>
<i class="last__logoTw fab fa-twitter"></i>
<i class="last__logoFb  fab fa-facebook-f"></i>
</div>
<div class="last__container">
<ul class="last__containerPlatform"> 
<li class="last__containerTitle">Platform <span class="last__containerPlatform-span"></span></li>
<li class="last__containerLi last__containerPlatformLi1">Book home</li>
<li class="last__containerLi last__containerPlatformLi2">Place</li>
<li class="last__containerLi last__containerPlatformLi3">Order</li>
<li class="last__containerLi last__containerPlatformLi4">Boards</li>
</ul>
<ul class="last__containerCompany"> 
<li class="last__containerTitle">Company</li>
<li class="last__containerLi last__containerCompanyLi1">About us</li>
<li class="last__containerLi last__containerCompanyLi2">Company</li>
<li class="last__containerLi last__containerCompanyLi3">Press & Blog</li>
<li class="last__containerLi last__containerCompanyLi4">Privacy Policy</li>
</ul>
<ul class="last__containerResources">
<li class="last__containerTitle">Resources</li>
<li class="last__containerLi last__containerResourcesLi1">Support</li>
<li class="last__containerLi last__containerResourcesLi2">Latest Updates</li>
<li class="last__containerLi last__containerResourcesLi3">Update Newsletter</li>
<li class="last__containerLi last__containerResourcesLi4">Deal Flow Management</li>
</ul>
<div class="lastone">
<span class="last__containerDot last__containerDot--1"></span> 
<span class="last__containerDot last__containerDot--2"></span>
<span class="last__containerDot last__containerDot--3"></span>
<span class="last__containerDot last__containerDot--4"></span>
<span class="last__containerDot last__containerDot--5"></span>
<span class="last__containerDot last__containerDot--6"></span>
<span class="last__containerDot last__containerDot--7"></span>
<span class="last__containerDot last__containerDot--8"></span>
<span class="last__containerDot last__containerDot--9"></span>
<span class="last__containerDot last__containerDot--A"></span>
<span class="last__containerDot last__containerDot--B"></span>
<span class="last__containerDot last__containerDot--C"></span>
</div>
</div>


<p class="footerr"> @ 2020- Made with by Mahadi</p>
</footer>
</template>

<script>
export default {
name:'Footer'
}
</script>

<style>
  .last {
    position: relative;
    top: 650px;
    left: -60px;
    width: 1440px;
    height: 400px;
    
}
.last__logo {
    position: absolute;
    width: 192px;
    height: 114px;
    left: 210px;
    top: 170px;
    font-family: Poppins;
    font-style: normal;
    font-weight: 500;
    font-size: 37px;
    line-height: 54px;
    color: #4270C9;
}
.last__logo-span {
 color: black;   
}
.last__logoIg {
    position: absolute;
    color:  #4270C9;
    top: 83px;
    left: -3px;
    font-size: 32px;
}
.last__logoIn {
    position: absolute;
    color: black;
    top: 90px;
    font-size: 20px;
    left: 50px;
}
.last__logoTw {
    position: absolute;
    color: black;
    top: 92px;
    font-size: 20px;
    left: 92px;
}
.last__logoFb {
    position: absolute;
    color: black;
    top: 80px;
    font-size: 20px;
    top: 90px;
    left: 135px;
}
.last__container {
    position: absolute;
    width: 1100px;
    height: 290px;
    top: 120px;
    left: 450px;
    background:#f7f6f6;
    opacity: 1;
    
}
.last__containerPlatform {
    position: absolute;
    width: 90px;
    height: 30px;
    left: 100px;
    top: 25px;
    
    font-family: Poppins;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 30px;
    letter-spacing: 0.025em;
    color: black;
}
.last__containerPlatform-span {
    position: absolute;
width: 36px;
height: 2.5px;
top: 32px;

background: #4270C9;
}
.last__containerCompany {
    position: absolute;
width: 104px;
height: 30px;
left: 300px;
top: 25px;
font-family: Poppins;
font-style: normal;
font-weight: 500;
font-size: 20px;
line-height: 30px;
letter-spacing: 0.025em;
color: #0E1717;
}
.last__containerResources {
    position: absolute;
width: 109px;
height: 30px;
left: 500px;
top: 25px;
font-family: Poppins;
font-style: normal;
font-weight: 500;
font-size: 20px;
line-height: 30px;
letter-spacing: 0.025em;
color: #0E1717;
}
.last__containerLi {
    position: absolute;
    font-family: Poppins;
font-style: normal;
font-weight: normal;
font-size: 16px;
line-height: 24px;
letter-spacing: 0.025em;
color: #5E5E5E;
list-style: none;

}
.last__containerPlatformLi1 {
    top: 50px;
    white-space: nowrap;
}
.last__containerTitle {
    list-style: none;
}
.last__containerPlatformLi2 {
    top: 85px;
}
.last__containerPlatformLi3 {
    top: 120px;
}
.last__containerPlatformLi4 {
    top: 155px;
}
.last__containerCompanyLi1 {
    top: 50px;
}
.last__containerCompanyLi2 {
    top: 85px;
}
.last__containerCompanyLi3 {
    top: 120px;
}
.last__containerCompanyLi4 {
    top: 155px;
    white-space: nowrap;
}
.last__containerResourcesLi1 {
    top: 50px;
} 
.last__containerResourcesLi2 {
    top: 85px;
    white-space: nowrap;
}
.last__containerResourcesLi3 {
    top: 120px;
    white-space: nowrap;
}
.last__containerResourcesLi4 {
    top: 155px;
    white-space: nowrap;
}
.footerr {
    position: relative;
width: 220px;
height: 21px;
left: 690px;
top: 440px;
padding-bottom: 50px;
font-family: Poppins;
font-style: normal;
font-weight: 500;
font-size: 14px;
line-height: 21px;
color: rgba(0, 0, 0, 0.5);
}
.last__containerDot {
    position: absolute;
width: 12px;
height: 11px;
left: 0px;
top: 0px;
border-radius: 100%;
background: #4270C9;
transform: matrix(1, 0, 0, -1, 0, 0);
}
.last__containerDot--1 {
    left: 780px;
    top:100px;
    width: 8px;
    height: 7px;
}
.last__containerDot--2 {
    left: 800px;
    top: 60px;
    width: 8px;
    height: 7px;
}
.last__containerDot--3 {
    left:805px;
    top:140px;
    width: 8px;
    height: 7px;
}
.last__containerDot--4 {
    left: 820px ;
    top: 100px;
    width: 8px;
    height: 7px;
}
.last__containerDot--5 {
    left: 850px;
    top: 90px;
    width: 8px;
    height: 7px;
}
.last__containerDot--6 {
    top: 105px;
    left: 865px;
    width: 8px;
    height: 7px;
}
.last__containerDot--7 {
    top: 120px;
    left: 850px;
    width: 8px;
    height: 7px;
}
.last__containerDot--8 {
    top: 130px;
    left: 867px;
    width: 8px;
    height: 7px;
}
.last__containerDot--9 {
    top: 125px;
    left: 890px;
    width: 8px;
    height: 7px;
}
.last__containerDot--A {
    top: 163px;
    left: 880px;
    width: 8px;
    height: 7px;
}
.last__containerDot--B {
    top: 160px;
    left: 840px; 
    width: 8px;
    height: 7px;   
}
.last__containerDot--C {
    top: 160px;
    left: 920px;
    width: 12px;
    height: 11px;
}

</style>