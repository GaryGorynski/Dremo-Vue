<template>
  <div class="rev">
    <section class="review">
      <div class="test1">
        <span class="test__containerDot test__containerDot--1"></span>
        <span class="test__containerDot test__containerDot--2"></span>
        <span class="test__containerDot test__containerDot--3"></span>
        <span class="test__containerDot test__containerDot--4"></span>
        <span class="test__containerDot test__containerDot--5"></span>
        <span class="test__containerDot test__containerDot--6"></span>
        <span class="test__containerDot test__containerDot--7"></span>
        <span class="test__containerDot test__containerDot--8"></span>
        <span class="test__containerDot test__containerDot--9"></span>
        <span class="test__containerDot test__containerDot--A"></span>
        <span class="test__containerDot test__containerDot--B"></span>
        <span class="test__containerDot test__containerDot--C"></span>
      </div>
      <i class="review__quote fas fa-quote-right"></i>
      <h3 class="review__heading">Clients review</h3>
      <p class="review__paragraph">
        Over 10,000 happy clients! Are you the next one?
      </p>
      <div class="review__imgBcg"></div>
      <img class="review__imgRight" src="/assets/ziomo.png" alt="noimg" />
      <img class="review__imgLeft" src="/assets/ziomalka.png" alt="noimg" />
      <div class="review__box">
        <p class="review__box-paragraph">
          <span class="review__box-paragraph-span">“Dremo</span> made my life
          easy.It helped me with the search for my first ever my dream 1BHK
          apartment Thanks to the team for providing smart search.”
        </p>
        <p class="review__box-paragraph2">Lee Morgan, Thinglogix, Inc.</p>
        <p class="review__box-paragraph3">New york, NY 10011</p>
        <span class="fa fa-star review__box-star"></span>
        <span class="fa fa-star review__box-star2"></span>
        <span class="fa fa-star review__box-star3"></span>
        <span class="fa fa-star review__box-star4"></span>
        <span class="fa fa-star review__box-star5"></span>
      </div>
      <p class="review__paragraphTwo">
        4.56/5.0
        <span class="fa fa-star review__paragraphTwo-star1"></span>
        <span class="fa fa-star review__paragraphTwo-star2"></span>
        <span class="fa fa-star review__paragraphTwo-star3"></span>
        <span class="fa fa-star review__paragraphTwo-star4"></span>
        <span class="fa fa-star-half review__paragraphTwo-halfstar"></span>
      </p>
      <button class="review__Btn">
        <span class="review__Btn-txt">Read 1,262 more reviews</span>
      </button>
      <h3 class="review__headingTwo">Still have a question ?</h3>
      <p class="review__paragraphThree">
        With a library of configurable features that conform to the
        Manufacturing and cost effectively.
      </p>
      <div class="review__subscribeBox">
        <input
          type="text"
          name="messageIn"
          class="review__subscribeBox-input"
          placeholder="Enter Your email adress"
        />
        <i class="far fa-envelope"></i>
        <button class="review__subscribeBoxBtn">
          <span class="review__subscribeBoxBtnTxt">Subscribe Now</span
          ><span class="review__subscribeBoxBtn-hoverr"></span
          ><i class="fas fa-arrow-right review__subscribeBoxBtn-hover"></i>
        </button>
      </div>
      <div class="tlo"></div>
    </section>
  </div>
</template>

<script>
export default {
  name: "Review",
};
</script>

<style>
.rev {
  display: flex;
}
.review {
  position: relative;
  width: 1339px;
  height: 967.92px;
  align-items: center;
  top: 70px;
}
.review__heading {
  position: relative;
  width: 291px;
  height: 60px;
  left: 925px;
  top: 210px;

  font-weight: 500;
  font-size: 42px;
  line-height: 60px;
  white-space: nowrap;
  /* identical to box height */

  color: #000000;
}
.review__quote {
  position: absolute;
  left: 1200px;
  right: 15.75%;
  top: 50px;
  bottom: 29.51%;
  font-size: 140px;
  color: #f3f3f3;
}
.review__paragraph {
  position: absolute;
  width: 383px;
  height: 24px;
  left: 930px;
  top: 280px;
  white-space: nowrap;
  font-weight: 500;
  font-size: 16px;
  line-height: 24px;
  font-size: 16px;
  /* identical to box height */

  color: #000000;
}
.review__imgBcg {
  position: absolute;
  width: 562px;
  height: 639px;
  background: rgba(248, 248, 248, 05);
  border-radius: 120px 41px 144px 120px;
  transform: matrix(0.86, -0.54, 0.5, 0.85, 0, 0);
  top: 300px;
  left: 120px;
}
.review__imgRight {
  position: absolute;
  left: 439px;
  top: 260px;
  border-radius: 5px;
  z-index: 1;
}
.review__imgLeft {
  position: absolute;
  top: 410px;
  left: 145px;
  border-radius: 5px;
}
.review__box {
  position: absolute;
  width: 434px;
  height: 319px;
  background: #ffffff;
  box-shadow: 0px 16px 24px rgba(112, 144, 176, 0.2);
  left: 878px;
  top: 420px;
  z-index: 1;
  border-radius: 10px;
}
.review__box-paragraph {
  position: relative;
  width: 363px;
  height: 108px;
  top: 60px;
  font-weight: normal;
  font-size: 16px;
  margin-left: 7%;
  line-height: 27px;
}
.review__box-paragraph-span {
  color: #42709c;
}
.review__box-paragraph2 {
  position: absolute;
  width: 203px;
  height: 27px;
  top: 190px;
  margin-left: 7%;

  font-weight: normal;
  font-size: 16px;
  line-height: 169.5%;

  letter-spacing: -0.03em;

  color: #000000;
}
.review__box-paragraph3 {
  position: absolute;
  width: 99px;
  height: 20px;
  margin-left: 7%;
  top: 225px;
  font-weight: normal;
  font-size: 12px;
  color: #cecece;
  letter-spacing: -0.03em;
  white-space: nowrap;
  line-height: 169.5%;
}
.review__box-star {
  position: relative;
  top: 260px;
  font-size: 8px;
  margin-left: 7%;
  color: #f1511b;
  padding-left: 1px;
}
.review__box-star2 {
  position: absolute;
  top: 260px;
  font-size: 8px;
  margin-left: 9%;
  color: #f1511b;
  padding-left: 1.5px;
}
.review__box-star3 {
  position: absolute;
  top: 260px;
  font-size: 8px;
  margin-left: 11%;
  color: #f1511b;
  padding-left: 1px;
}
.review__box-star3 {
  position: absolute;
  top: 260px;
  font-size: 8px;
  margin-left: 11%;
  color: #f1511b;
  padding-left: 2px;
}
.review__box-star4 {
  position: absolute;
  top: 260px;
  font-size: 8px;
  margin-left: 13%;
  color: #f1511b;
  padding-left: 3px;
}
.review__box-star5 {
  position: absolute;
  top: 260px;
  font-size: 8px;
  margin-left: 15%;
  padding-left: 4px;
  color: #f1511b;
}

.review__paragraphTwo {
  position: relative;
  width: 64px;
  height: 31px;

  font-family: "Roboto";
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 169.5%;
  top: 710px;
  left: 850px;
}
.fa-star {
  position: absolute;
  color: #f15118;
}
.review__paragraphTwo-star1 {
  top: 5px;
  left: -100px;
  font-size: 17px;
}
.review__paragraphTwo-star2 {
  top: 5px;
  left: -50px;
  font-size: 17px;
  z-index: 1;
}
.review__paragraphTwo-star3 {
  top: 5px;
  left: -75px;
  font-size: 17px;
  z-index: 1;
}
.review__paragraphTwo-star4 {
  top: 5px;
  left: -125px;
  font-size: 17px;
  z-index: 1;
}
.review__paragraphTwo-halfstar {
  top: 5px;
  left: -25px;
  font-size: 17px;
  position: absolute;
  color: #f15118;
  z-index: 1;
}
.review__Btn {
  position: relative;
  width: 210px;
  height: 60px;
  top: 700px;
  left: 690px;
  background: #4270c9;
  box-shadow: 4px 20px 32px rgba(158, 175, 201, 0.2);
  border-radius: 60px;
  border: none;
}
.review__Btn-txt {
  position: absolute;
  font-size: 14px;
  font-weight: 300;
  font-style: normal;
  color: #ffffff;
  top: 21px;
  left: 26px;
  letter-spacing: -0.03em;
  list-style: none;
}
.review__Btn:hover {
  background-color: white;
  transition: 0.3s;
  box-shadow: 4px 20px 32px rgba(158, 175, 201, 0.7);
}
.review__Btn:hover .review__Btn-txt {
  transition: 0.3s;
  color: #4270c9;
}

.review__headingTwo {
  position: absolute;
  width: 441px;
  height: 53px;
  left: 484px;
  top: 1050px;

  font-weight: 600;
  font-size: 40px;
  line-height: 132.5%;
  color: #101010;
}
.review__paragraphThree {
  position: absolute;
  left: 305px;
  top: 1150px;
  width: 810px;
  text-align: center;
  font-weight: normal;
  font-size: 22px;
  line-height: 200.5%;
  color: #3c3c3c;
}

.review__subscribeBox {
  position: absolute;
  width: 852px;
  height: 124px;
  left: 293px;
  top: 1370px;

  background: white;
  box-shadow: 0px 4px 100px #f2f2f5;
  border-radius: 5px;
}
.review__subscribeBox-input {
  position: absolute;
  width: 224px;
  height: 35px;
  left: 115px;
  top: 50px;
  font-weight: normal;
  font-size: 18px;
  line-height: 15px;
  color: #b6b6b6;
  border: none;
  outline: none;
}
.fa-envelope {
  position: absolute;
  left: 53px;
  top: 47px;
  color: #5583dc;
  font-size: 40px;
}

.review__subscribeBoxBtn {
  position: relative;
  height: 61px;
  width: 200px;
  top: 35px;
  left: 600px;
  background: #5583dc;
  border-radius: 60px;
  border: none;
  color: #ffffff;
}
.review__subscribeBoxBtnTxt {
  position: relative;
  left: 45px;
  bottom: 7px;
  font-weight: 300;
  font-size: 14px;
}
.review__subscribeBoxBtn-hover {
  position: relative;
  right: 117px;
  bottom: 3px;
  color: white;
  background-color: rgba(190, 202, 231, 0.1);
  font-size: 26px;
  font-weight: 600;
  margin-top: 5px;
  border-style: solid;
  border-radius: 40px 40px;
  border-width: 15px;
  border-color: rgba(190, 202, 231, 0.2);
}
.review__subscribeBoxBtn-hoverr {
  position: absolute;
  right: 153px;
  bottom: 19px;
  width: 25px;
  height: 25px;
  background: rgba(190, 202, 231, 0.2);
  margin-top: 5px;
  border-radius: 50%;
}

.review__subscribeBoxBtn:hover {
  background-color: white;
  color: #5583dc;
  transition: 0.3s;
  box-shadow: 4px 20px 32px rgba(158, 175, 201, 0.7);
}
.review__subscribeBoxBtn:hover .review__subscribeBoxBtn-hover {
  transition: 0.3s;
  background-color: white;
  border-color: white;
  color: #5583dc;
}
.test1 {
  position: relative;
  bottom: 4250px;
  right: 70px;
}

.test__containerDot {
  position: absolute;
  width: 5px;
  height: 4px;
  border-radius: 100%;
  background: #4270c9;
  transform: matrix(1, 0, 0, -1, 0, 0);
}
.test__containerDot--1 {
  left: 58px;
  top: 4200px;
  width: 7px;
  height: 6px;
}
.test__containerDot--2 {
  left: 80px;
  top: 4160px;
  width: 8px;
  height: 7px;
}
.test__containerDot--3 {
  left: 85px;
  top: 4240px;
  width: 8px;
  height: 7px;
}
.test__containerDot--4 {
  left: 100px;
  top: 4200px;
  width: 8px;
  height: 7px;
}
.test__containerDot--5 {
  left: 130px;
  top: 4190px;
  width: 8px;
  height: 7px;
}
.test__containerDot--6 {
  top: 4205px;
  left: 145px;
  width: 8px;
  height: 7px;
}
.test__containerDot--7 {
  top: 4220px;
  left: 130px;
  width: 8px;
  height: 7px;
}
.test__containerDot--8 {
  top: 4230px;
  left: 167px;
  width: 8px;
  height: 7px;
}
.test__containerDot--9 {
  top: 4225px;
  left: 190px;
  width: 8px;
  height: 7px;
}
.test__containerDot--A {
  top: 4263px;
  left: 180px;
  width: 8px;
  height: 7px;
}
.test__containerDot--B {
  top: 4260px;
  left: 140px;
  width: 8px;
  height: 7px;
}
.test__containerDot--C {
  top: 4260px;
  left: 220px;
  width: 12px;
  height: 11px;
}
</style>
