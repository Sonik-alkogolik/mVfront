<template>
    <div class="footer">
      <div class="footer-wrap">
          <div class="footer-nav">
            <div class="footer-list-link">
              <ul>
                <li><a href="#" title="#">WORK</a></li>
                <li><a href="#" title="#">About</a></li>
                <li><a href="#" title="#">Services</a></li>
                <li><a href="#" title="#">Blog</a></li>
                <li><a href="#" title="#">Contact</a></li>
              </ul>
            </div>

            <div class="social-network">
              <a href="#" title="#"><img src="@/assets/facebook.svg"  title="itcon-facebook"/></a>
              <a href="#" title="#"><img src="@/assets/twitter.svg"  title="itcon-twitter"/></a>
              <a href="#" title="#"><img src="@/assets/instagram.svg"  title="itcon-inst"/></a>
            </div> 
          </div>
      </div>
    </div>
</template>

<script>
export default {
  components:{

  }

}
</script>

<style>
  .footer {
    max-width: 1600px;
    width: 100%;
    height: 220px;
    display: flex;
    justify-content: center;
  }
  .footer-wrap {
    max-width: 1210px;
    width: 100%;
    height: 220px;
    display: flex;
    justify-content: space-between;
  
  }
  .footer-nav {
    max-width: 1210px;
    width: 100%;
    height: 220px;
    display: flex;
      justify-content: space-between;

  }
  .footer-list-link {
    max-width: 610px;
    width: 100%;
    height: 220px;
    display: flex;

  }
    .footer-list-link>ul{
    max-width: 545px;
    width: 100%;
    height: 170px;
    display: flex;
    justify-content: space-between;
    align-items: center;

  }
  .footer-list-link>ul>li{
      font-family: 'Poppins';
font-style: normal;
font-weight: 600;
font-size: 18px;
line-height: 38px;
letter-spacing: 0.03em;
text-transform: uppercase;

color: #FFFFFF;

opacity: 0.5;
  }
   .footer-list-link>ul>li>a{
    font-family: 'Poppins';
font-style: normal;
font-weight: 600;
font-size: 18px;
line-height: 38px;
letter-spacing: 0.03em;
text-transform: uppercase;

color: #FFFFFF;

opacity: 0.5;
  }

  .social-network {
    max-width: 610px;
    width: 100%;
    height: 170px;
    display: flex;
    align-items: center;
    justify-content: flex-end;
  }
  .social-network>a>img{
      width: 32px;
      height: 32px;
      margin:0 10px;
  }
</style>