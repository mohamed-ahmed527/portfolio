<template>
  <div id="Projects" class="parent">
    <div class="container">
      <h1> Projects </h1>

      <div class="row">
        <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12" >
          <div class="project photo">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <img src="../assets/imgs/pro13.png">
            <a href="https://pullo-pro.netlify.app/" target="_blank">View Site</a>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12" >
          <div class="project photo">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <img src="../assets/imgs/pro1.png">
            <a href="https://project-champ.netlify.app/" target="_blank">View Site</a>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12" >
          <div class="project photo">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <img src="../assets/imgs/pro7.png">
            <a href="https://artfactory.netlify.app/" target="_blank">View Site</a>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12" >
          <div class="project photo">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <img src="../assets/imgs/pro11.png">
            <a href="https://spicyo-pro.netlify.app/" target="_blank">View Site</a>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12" >
          <div class="project photo">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <img src="../assets/imgs/pro12.png">
            <a href="https://taskia-pro.netlify.app/" target="_blank">View Site</a>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12" >
          <div class="project photo">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <img src="../assets/imgs/pro8.png">
            <a href="https://denproject.netlify.app/" target="_blank">View Site</a>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12" >
          <div class="project photo">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <img src="../assets/imgs/pro2.png">
            <a href="https://mohamed-ahmed527.github.io/softlanding/" target="_blank">View Site</a>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12" >
          <div class="project photo">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <img src="../assets/imgs/pro3.png">
            <a href="https://mohamed-ahmed527.github.io/known/" target="_blank">View Site</a>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12" >
          <div class="project photo">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <img src="../assets/imgs/pro4.png">
            <a href="https://mohamed-ahmed527.github.io/education/" target="_blank">View Site</a>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12" >
          <div class="project photo">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <img src="../assets/imgs/pro5.png">
            <a href="https://mohamed-ahmed527.github.io/hospital/" target="_blank">View Site</a>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12" >
          <div class="project photo">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <img src="../assets/imgs/pro6.png">
            <a href="https://mohamed-ahmed527.github.io/watches/" target="_blank">View Site</a>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12" >
          <div class="project photo">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <img src="../assets/imgs/pro9.png">
            <a href="https://mohamed-ahmed527.github.io/arsha/" target="_blank">View Site</a>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 col-sm-6 col-xs-12" >
          <div class="project photo">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <img src="../assets/imgs/aklni.png">
            <a href="https://mohamed-ahmed527.github.io/akelni/" target="_blank">View Site</a>
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
      color: gold;
      margin-bottom: 100px;
      font-family: 'Reggae One', cursive;
    }
    .row{
      display: flex;
      flex-wrap: wrap;
      .col-xs-12{
        .project{
          position: relative;
          margin-bottom: 25px;
          img{
            display: block;
            width: 100%;
            transition: 0.5s all;
            transform: scale(0.95);
          }
          a{
            position: absolute;
            top: 42%;
            left: 35%;
            display: block;
            opacity: 0;            
            text-decoration: none;
            padding: 7px 15px;
            background-color:  gold;
            color: white;
            transition: 0.5s all;
          }
        &:hover{         
          img{            
            transform: scale(1);
            transition-timing-function: ease-in-out;
          }
          a{
            opacity: 1;
            transition-timing-function: ease-in-out;
          }
        }
        }
      }
    }
  }
}
/***********/
.photo{
  margin:30px auto;
  position: relative;
}
.photo span{
  position: absolute;
  background-color: gold;
  transition: 0.7s all;
  z-index:100;
}
.photo span:nth-of-type(1){
  top: 0;
  left: 0;
  width: 10%;
  height: 1.3%;
}
.photo span:nth-of-type(2){
  bottom: 0;
  right: 0;
  width: 10%;
  height: 1.3%;
}
.photo span:nth-of-type(3){
  bottom: 0;
  right: 0;
  width: 1%;
  height: 12%;
}
.photo span:nth-of-type(4){
  top: 0;
  left: 0;
  width: 1%;
  height: 12%;
}
.photo:hover span:nth-of-type(1) , .photo:hover span:nth-of-type(2){
  width: 100%;
}
.photo:hover span:nth-of-type(3) , .photo:hover span:nth-of-type(4){
  height: 100%;
}
</style>