<template>
<div>
<AppHeader/>
<LFhome/>
<How-it-works/>
<Booking/>
<Featured/>
<Review/>
<Footer/>
</div>

</template>

<script> 
import AppHeader from '../components/AppHeader.vue'
import LFhome from '../components/LFhome.vue'
import Howitworks from '../components/How-it-works.vue'
import Booking from '../components/Booking.vue'
import Featured from '../components/Featured.vue'
import Review from '../components/Review.vue'
import Footer from '../components/Footer.vue'
export default {
  components: {
    AppHeader,
    LFhome,
    Howitworks,
    Booking,
    Featured,
    Review,
    Footer
  }
}
</script>


<style>


body { position: relative;
width: 1440px;
height: 6318px;
margin: 0px;
padding: 0px;
background: white;
border-radius: 30px; }
ul {
  list-style-type: none;
}

</style>
