<template>
  <div id="About" class="parent">
    <div class="container">
      <h1> About </h1>
      <div class="row">
        <div class="col-md-6">
          <div class="about_text" data-aos="fade-right" data-aos-duration="1500">
            <h2> I'm Mohamed Ahmed </h2>
            <p> I'm a Junior web designer, if you have a site. If you want to create a site that faces your company, or you have an idea that you want to implement, then you are in the right place. What you want will be done as quickly as possible and with the highest quality. Technical support will also be present.</p>
          </div>
        </div>

        <div class="col-md-5">
          <div class="about_img" data-aos="fade-left" data-aos-duration="1500">
            <img src="../assets/imgs/about.jpg"/>
          </div>
        </div>
      </div>
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
  margin-top: 150px;
  margin-bottom: 250px;
  .container{
    h1{
      margin-bottom: 100px;
      color: white;
      text-align: center;
      font-size: 45px;
      font-weight: 700;
      color: gold;
      font-family: 'Reggae One', cursive;


    }
    .row{
      display: flex;
      justify-content: space-around;
      .col-md-5{
        .about_img{
          img{
            width: 100%;
          }
        }
      }
      .col-md-6{
        .about_text{
          h2{
            line-height: 1;
            text-align: left;
            font-size: 35px;
            letter-spacing: 1px;
            font-family: 'Courier New', Courier, monospace;
            color: #b0a308;

          }
          p{
            color: #c4c2bd;
            text-align: left;
            line-height: 1.9;
            font-size: 17px;
            font-family: sans-serif;
            letter-spacing: 1px;
          }
        }

      }
    }
  }
}
</style>