<template>
  <div id="Skills" class="parent">
    <div class="container">
      <h1> Skills </h1>
      <div class="row">
        <div class="col-md-6">
          <div class="skills_img">
            <img src="../assets/imgs/skills.jpg" />
          </div>
        </div>
        <div class="col-md-6">          
          <div class="skills_text">
            <p>I design websites using Html5 , Css3 , Javascirpt , Jquery , Bootstrab4 , Scss , Vue.js And using Ui / Ux with Adobe xd</p>
            <div class="list" data-aos="flip-left" data-aos-duration="1300">
              <div> Html 5</div>
            </div>
            <div class="list" data-aos="flip-left" data-aos-duration="1300">
              <div style="width:100% !important"> Css 3 </div>
            </div>
            <div class="list" data-aos="flip-left" data-aos-duration="1300">
              <div style="width:100% !important"> Javascirpt </div>
            </div>
            <div class="list" data-aos="flip-left" data-aos-duration="1300">
              <div style="width:100% !important"> Jquery </div>
            </div>
            <div class="list" data-aos="flip-left" data-aos-duration="1300">
              <div style="width:100% !important"> Bootstrab 4 </div>
            </div>
            <div class="list" data-aos="flip-left" data-aos-duration="1300">
              <div style="width:100% !important"> Scss </div>
            </div>
            <div class="list" data-aos="flip-left" data-aos-duration="1300">
              <div style="width:100% !important"> Vue.js </div>
            </div>
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
  margin-bottom: 250px;
  .container{
    >h1{
      margin-bottom: 100px;
      color: gold;
      font-family: 'Reggae One', cursive;
    }
    .row{
      .col-md-6{
        margin-bottom: 30px;
        .skills_img{
          img{
            width: 100%;
          }
        }
      }
      .col-md-6{
        .skills_text{
          p{
            margin-top: 0px;
            text-align: left;
            color: #c4c2bd;
            line-height: 1.5;
            font-size: 17px;
            font-family: sans-serif;
            letter-spacing: 1px;
          }
          .list{
            margin-bottom: 10px;
            background-color: grey;
            border-radius: 5px;
            div{
              border-radius: 5px;
              font-family: system-ui;
              text-align: left;
              padding: 3px 5px;
              background-color:#007bff;
              color: white;
            }
          }
        }
      }
    }
  }
}
</style>