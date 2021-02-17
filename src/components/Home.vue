<template>
  <div id="Home" class="parent">
    <div class="container">
      <h1>
         HELLO! I'M <br>
          <h2 data-aos="fade-up" data-aos-duration="1500" data-aos-mirror="true"> Mohamed Ahmed </h2> 
          <h3 data-aos="flip-down" data-aos-duration="1700"   data-aos-mirror="true"> Web Designer </h3>
      </h1>
    </div>
  </div>
</template>
<script>
export default {
  name:"parent"
}
</script>
<style lang="scss" scoped>
.parent{
  .container{
    h1{
      margin: 250px 0px;
      font-size: 30px;
      font-family: system-ui;
      line-height: 1.5;
      letter-spacing: 4px;
      color: grey;
      h2{
        color: white;
        font-size: 60px;
        font-family: 'Montserrat Alternates', sans-serif;
        line-height: 1.5;
        letter-spacing: 4px;
        font-weight: 700;
      }
      h3{
        line-height: 3;
        letter-spacing: 9px;
        font-size: 20px;
        color: gold;
        font-family: 'Lobster', cursive;
      }
    }
  }
}
@media (max-width:992px) {
 .parent .container h1{
   margin: 170px 0px;
 } 
}
</style>