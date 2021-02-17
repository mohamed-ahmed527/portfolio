<template>
  <div class="parent">
    <div class="container">
      <span class="menu"> <i class="fa fa-bars" aria-hidden="true"></i> </span>
      <nav>
        <div class="logo">
          <img src="../assets/imgs/logoimg.jpg"/>
        </div>
        <div class="rightnav">
          <ul>
            <li><a href="#Home"> Home </a></li>
            <li><a href="#About"> About </a></li>
            <li><a href="#Skills"> Skills </a></li>
            <li><a href="#Projects"> Projects </a></li>
            <li><a href="#Contact"> Contact </a></li>
          </ul>
        </div>
      </nav>
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
  nav{
    overflow: hidden;
    .logo{
      width: 19%;
      float: left;
      overflow: hidden;
      img{
        width: 100%;
        transform: scale(1.1);
      }
    }
    .rightnav{
      float: right;
      ul{
        margin: 0px;
        overflow: hidden;
        li{
          color: white;
          display: inline;
          float: left;
          list-style: none;
          font-size: 20px;
          font-family: system-ui;
          margin-left:10px;
          a{
            padding: 20px;
            color: unset; 
            text-decoration: none;
            display: block;
            width: 100%;
          }
          &:hover{
            color: gold;
            transition: 0.3s all;
          }
        }
      }
    }
  }
}
@media (max-width:992px) {
  .parent nav .logo{
    width: 45%;
  }
  .parent nav .rightnav{
    display: none;
    float: left;
    ul{
      padding: 0px;
      li{
        margin-left: 0px;
        display:block;
        width: 100%;
        text-align: left;
      }
    }
  }
}
/**************menu*****************/
.menu{
  cursor: pointer;
  font-size: 35px;
  color: white;
  float: right;
}
@media (min-width:993px) {
  .menu{
    display: none;
  }
}
</style>