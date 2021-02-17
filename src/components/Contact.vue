<template>
  <div id="Contact" class="parent">
    <div class="container">
      <h1> Contact </h1>

    </div>
    <div class="footer">
      <span> <a href="https://www.facebook.com/profile.php?id=100007911797084" target="_blank"><i class="fab fa-facebook"></i></a></span>
      <span><a href="https://twitter.com/Muhamme96682009" target="_blank"><i class="fab fa-twitter"></i></a></span>
      <span><a href="https://mail.google.com/mail/u/0/#inbox" target="_blank"><i class="fa fa-envelope" aria-hidden="true"></i></a></span>
      <span><a href="https://www.linkedin.com/in/mohamed-ahmed-1763b51b7" target="_blank"><i class="fab fa-linkedin"></i></a></span>
      <span><a href="https://wa.me/+201091925941?text=" target="_blank"><i class="fab fa-whatsapp"></i></a></span>
      <span><a href="https://mostaql.com/u/mohamed_ahmed72" target="_blank"> <img src="../assets/imgs/mostaql.png"/> </a>  </span>
      <p>© 2020 copyright all right reserved</p>
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
    >h1{
      color: gold;
      font-family: 'Reggae One', cursive;
      margin-bottom: 100px;
    }
}
  .footer{
    background-color: transparent;
    padding: 50px 0px;   
    h1{
      color: white;
      margin-bottom: 50px;
      letter-spacing: 5px;
    }
    span a{
      font-size: 26px;
      color: white;
      margin: 0px 10px;
      transition: 0.2s all;
      &:hover{
        transition-timing-function: ease-in-out;
        color:  gold;
      }

    }  
    p{
      margin-top: 70px;
      margin-bottom: 0px;
      font-weight: 600;
      text-align: center;
      color: white;
      letter-spacing: 2px;
      }
      >span:last-of-type{
        width: 50px;
        img{
          width: 50px;
        }
      }
  }
}
@media (max-width:992px) {
  .parent .container form{
    padding: 0px 0px;
  }
}
</style>