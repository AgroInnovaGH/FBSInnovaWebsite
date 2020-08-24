<template>
  <footer
    class="footer footer-distributed"
    :class="{ [`footer-${type}`]: type }"
    :data-background-color="backgroundColor"
  >

      <div class="footer-left">

        <!--<image-->
        <img src="@/assets/img/fbs_innova_full.png" width="150px" class="margin"/>

          <p class="footer-company-name"><a target="_blank" href="http://agroinnovagh.com">AgroInnova &copy; 2019</a></p>
      </div>

      <div class="footer-center">

        <div>
          <i class="fa fa-map-marker"></i>
          <p><span> No. 19 Banana Avenue,  </span>East Legon -Ghana</p>
        </div>

        <div>
          <i class="fa fa-phone"></i>
          <p>+233 24 09 56 276 </p>
        </div>

        <div>
          <i class="fa fa-envelope"></i>
          <p><a href="mailto:info@fbsinnova.com">info@fbsinnova.com</a></p>
        </div>

      </div>

      <div class="footer-right">

        <p class="footer-company-about">
          <span>FBSINNOVA</span>
          Learn, track, diversify!.
        </p>



      </div>

    </footer>
</template>
<script>
export default {
  props: {
    backgroundColor: String,
    type: String
  },
  data() {
    return {
      leaf: {
        type: String,
        default: require("@/assets/img/fbs_innova.png")
      },
      year: new Date().getFullYear()
    };
  }
};
</script>
<style>

    a:hover{
        text-decoration:none !important;
    }
  .footer-distributed{
    background-color: transparent;
    box-shadow: 0 1px 1px 0 rgba(0, 0, 0, 0.12);
    box-sizing: border-box;
    width: 100%;
    text-align: left;
    font: bold 12px sans-serif;

    padding: 15px 100px;
    margin-top: 20px;
  }

  .footer-distributed .footer-left,
  .footer-distributed .footer-center,
  .footer-distributed .footer-right{
    display: inline-block;
    vertical-align: top;
  }

  /* Footer left */

  .footer-distributed .footer-left{
    width: 40%;
  }

  /* The company logo */

  .footer-distributed h3{
    color:  #ffffff;
    font: normal 14px 'OpenSans', cursive;
    margin: 0;
  }

  /* Footer links */

  .footer-distributed .footer-links{
    color:  #ffffff;
    margin: 20px 0 12px;
    padding: 0;
  }

  .footer-distributed .footer-links a{
    display:inline-block;
    line-height: 0.1;
    text-decoration: none;
    color:  inherit;
  }

  .footer-distributed .footer-company-name{
    color:  #8f9296;
      text-decoration:none;
    font-size: 14px;
    font-weight: normal;
    margin-top: 100px;
  }

  /* Footer Center */

  .footer-distributed .footer-center{
    width: 35%;
  }

  .footer-distributed .footer-center i{
    color:  #92999f;
    font-size: 16px;
    width: 38px;
    height: 38px;
    border-radius: 50%;
    text-align: center;
    line-height: 42px;
    margin: 10px 15px;
    vertical-align: middle;
  }

  .footer-distributed .footer-center i.fa-envelope{
    font-size: 17px;
    line-height: 38px;
  }

  .footer-distributed .footer-center p{
    display: inline-block;
    color:  #92999f;
    vertical-align: middle;
    margin:0;
  }

  .footer-distributed .footer-center p span{
    display:block;
    font-weight: normal;
    font-size:14px;
    line-height:2;
  }

  .footer-distributed .footer-center p a{
    color:  #25d366;
    text-decoration: none;;
  }


  /* Footer Right */

  .footer-distributed .footer-right{
    width: 20%;
  }

  .footer-distributed .footer-company-about{
    line-height: 20px;
    color:  #92999f;
    font-size: 13px;
    font-weight: normal;
    margin: 0;
  }

  .footer-distributed .footer-company-about span{
    display: block;
    color:  #92999f;
    font-size: 14px;
    font-weight: bold;
    margin-bottom: 20px;
  }

  .footer-distributed .footer-icons{
    margin-top: 25px;
  }

  .footer-distributed .footer-icons a{
    display: inline-block;
    width: 35px;
    height: 35px;
    cursor: pointer;
    background-color:  #33383b;
    border-radius: 2px;

    font-size: 20px;
    color: #ffffff;
    text-align: center;
    line-height: 35px;

    margin-right: 3px;
    margin-bottom: 5px;
  }

  /* If you don't want the footer to be responsive, remove these media queries */

  @media (max-width: 880px) {

    .footer-distributed {
      font: bold 14px sans-serif;
    }

    .footer-distributed .footer-left,
    .footer-distributed .footer-center,
    .footer-distributed .footer-right {
      display: block;
      width: 100%;
      margin-bottom: 40px;
      text-align: center;
    }

    .footer-distributed .footer-center i {
      margin-left: 0;
    }
  }
</style>
