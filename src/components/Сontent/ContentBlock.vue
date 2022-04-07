<template>
  <div class="content-block">
    <div class="block-cart-wrap">
      <div class="block-cart-item">

        <div class="item-cart-wrap">
            <div class="cart-img">
              <img src="@/assets/img-cart.svg" title="#">
            </div>
            <div class="cart-title">
                  <span>Photos</span>
            </div>
            <div class="cart-deskription">
              <p>Vestibulum suscipit tortor magna, quis pellentesque arcu volutpat ac. Tempus leo erat, sit amet ullamcorper nisl.</p>
            </div>
            <div class="cart-button">
                <button>Button</button>
            </div>
        </div>
        <div class="item-cart-wrap">
            <div class="cart-img">
              <img src="@/assets/cart-video.svg" title="#">
            </div>
            <div class="cart-title">
                  <span>Videos</span>
            </div>
            <div class="cart-deskription">
              <p>Vestibulum suscipit tortor magna, quis pellentesque arcu volutpat ac. Tempus leo erat, sit amet ullamcorper nisl.</p>
            </div>
            <div class="cart-button">
                <button>Button</button>
            </div>
        </div>
        <div class="item-cart-wrap">
            <div class="cart-img">
              <img src="@/assets/cart-download.svg" title="#">
            </div>
            <div class="cart-title">
                  <span>Downloads </span>
            </div>
            <div class="cart-deskription">
              <p>Vestibulum suscipit tortor magna, quis pellentesque arcu volutpat ac. Tempus leo erat, sit amet ullamcorper nisl.</p>
            </div>
            <div class="cart-button">
                <button>Button</button>
            </div>
        </div>

      </div>
    </div>

    <div class="block-quote">
      <div class="block-quote-wrap">
        <div class="block-quote-logo">
          <img src="@/assets/quotes.svg" title="#" />
        </div>
        <div class="block-quote-text"> 
          <p>In hac habitasse platea dictumst. Phasellus finibus ipsum enim, non pretium massa mattis non. Curabitur ut tempus ex. Nunc dictum est enim, consectetur convallis odio mollis tempus!</p>
        </div>
        <div class="quote-name">
          <span>Jim Gordon (GCPD)</span>
        </div>
         </div>
    </div>

    <div class="from-blog">
        <div class="from-blog-wrpaer">
              <div class="from-blog-title">
                <div class="line"></div>
                <h2>From the blog</h2>
              </div>
              <div class="form-blog-item">
                <div class="form-blog-img">
                  <img src="#" title="#" />
                </div>
                <div class="form-blog-deskription">
                  <div class="form-desk-title">
                      <span>title of a post</span>
                  </div>

                  <div class="form-desk-text">
                      <p>In hac habitasse platea dictumst. Phasellus finibus ipsum enim, non pretium massa mattis non. Curabitur ut tempus ex. Nunc dictum est enim, consectetur convallis odio mollis tempus.</p>
                    </div>
                    <div class="form-desk-btn">
                      <button>Read more</button>
                    </div>

                </div>
              </div>
              <div class="form-blog-item">
                <div class="form-blog-img">
                  <img src="#" title="#" />
                </div>
                <div class="form-blog-deskription">
                  <div class="form-desk-title">
                      <span>title of a post</span>
                  </div>

                  <div class="form-desk-text">
                      <p>In hac habitasse platea dictumst. Phasellus finibus ipsum enim, non pretium massa mattis non. Curabitur ut tempus ex. Nunc dictum est enim, consectetur convallis odio mollis tempus.</p>
                    </div>
                    <div class="form-desk-btn">
                      <button>Read more</button>
                    </div>

                </div>
              </div>
              <div class="form-blog-item">
                <div class="form-blog-img">
                  <img src="#" title="#" />
                </div>
                <div class="form-blog-deskription">
                  <div class="form-desk-title">
                      <span>title of a post</span>
                  </div>

                  <div class="form-desk-text">
                      <p>In hac habitasse platea dictumst. Phasellus finibus ipsum enim, non pretium massa mattis non. Curabitur ut tempus ex. Nunc dictum est enim, consectetur convallis odio mollis tempus.</p>
                    </div>
                    <div class="form-desk-btn">
                      <button>Read more</button>
                    </div>

                </div>
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
.content-block  {
  max-width: 1450px;
  width: 100%;
  height: auto;
  display: flex;
  flex-direction: column;
  background: #FFFFFF;
}
.block-cart-wrap {
 max-width: 1400px;
  width: 100%;
  height: auto;
  margin: 0 auto;
  display: flex;
  justify-content: center;
}
.block-cart-item  {
  max-width: 1210px;
  width: 100%;
  height: 690px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  position: relative;
}
.item-cart-wrap  {
  max-width: 363px;
  width: 100%;
  height: 450px;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
  background: #F6F6F6;
  border-radius: 6px;
}
.cart-img {
  max-width: 110px;
  width: 100%;
  height: 110px;
  background: #FFFFFF;
  border-radius: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  transform: translateY(-50px);
  
}
.cart-img>img{
    width: 40px;
    height: 32px;
}
.cart-title  {
    max-width: 220px;
    width: 100%;
    height: 75px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
.cart-title>span{
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  font-size: 30px;
  line-height: 36px;
  text-align: center;
  text-transform: uppercase;
  color: #353A3F;
}
.cart-deskription{
  max-width: 250px;
  width: 100%;
  height: 230px;
  display: flex;
  flex-wrap: wrap;
}
.cart-deskription>p{
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 30px;
  text-align: center;
  color: #5A5F65;
}
.cart-button {
  max-width: 160px;
  width: 100%;
  height: 65px;
  display: flex;
  justify-content: center;
  background: #4CB481;
  border-radius: 100px;
  margin-bottom: 60px;
}
.cart-button>button{
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  font-size: 18px;
  line-height: 36px;
  text-align: center;
  text-transform: uppercase;
  background:#4CB481;
  color: #FFFFFF;
  cursor: pointer;
}


.block-quote{
  max-width: 1450px;
  width: 100%;
  height: 600px;
  display: flex;
  flex-direction: column;
  background: #353A3F;
  justify-content: center;
  align-items: center;
}
.block-quote-wrap{
  max-width: 810px;
  width: 100%;
  height: 320px;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: space-between;
}
.block-quote-logo  {
  max-width:48px;
  width:100%;
  height: 39px;
}
.block-quote-logo>img{
  display: block;
  width: 100%;

}
.block-quote-text  {
  max-width: 766px;
  width: 100%;
  height: 180px;
  display: flex;
  flex-wrap: wrap;
  text-align:left;
}
.block-quote-text>p{
  font-family: 'Poppins';
  font-style: italic;
  font-weight: 300;
  font-size: 28px;
  line-height: 38px;
  color: #FFFFFF;

}

.quote-name  {
  max-width: 766px;
  width: 100%;
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: flex-start;

}
.quote-name>span{
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 500;
  font-size: 20px;
  line-height: 38px;
  color: #8C9198;
  display: flex;
  align-items: flex-start;
  flex-direction: column-reverse;

}
.quote-name>span::after{
    content: '';
    width: 60px;
    height: 4px;
    background: #8C9197;
    border-radius: 2px;
}

.from-blog {
  max-width: 1450px;
  width: 100%;
  height: 1496px;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background: #FFFFFF;

}
.line {
  width: 60px;
  height: 4px;
  background: #4CB481;
  border-radius: 2px;
  margin-top: 0px;
  margin-bottom: 25px;
}

.from-blog-wrpaer {
  max-width: 1210px;
  width: 100%;
  height: 1260px;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: space-between;

}
.from-blog-title {
  max-width: 565px;
  width: 100%;
  height: 90px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;

}
.from-blog-title>h2{
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 600;
    font-size: 44px;
    line-height: 44px;
    display: flex;
    align-items: center;
    text-transform: uppercase;
    color: #353A3F;
}
.form-blog-item  {
  max-width: 1210px;
  width: 100%;
  height: auto;
  display: flex;
  justify-content: space-between;

}
.form-blog-img  {
  max-width: 565px;
  width: 100%;
  height: 330px;
  display: flex;
}
.form-blog-img>img{
  display: block;
  width: 100%;
  background: #C4C4C4;
  border-radius: 6px;
}
.form-blog-deskription  {
  max-width: 565px;
  width: 100%;
  height: 300px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;

}
.form-desk-title  {
  max-width: 565px;
  width: 100%;
  height: 92px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
.form-desk-title>span{
font-family: 'Poppins';
font-style: normal;
font-weight: 600;
font-size: 30px;
line-height: 44px;
text-transform: uppercase;
color: #353A3F;
}
.form-desk-text  {
  max-width: 565px;
  width: 100%;
  height: 140px;
  flex-direction: column;
  justify-content: flex-start;
  text-align: left;

}
.form-desk-text>p{
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 25px;
  letter-spacing: 0.02em;
  color: #5A5F65;
}
.form-desk-btn  {
  max-width: 175px;
  width: 100%;
  height: 75px;
  display: flex;
  justify-content: center;
  text-align: center;
  align-items: center;
}
.form-desk-btn>button{
   max-width: 175px;
  width: 100%;
  height: 60px;
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  font-size: 18px;
  line-height: 36px;
  text-align: center;
  text-transform: uppercase;
  color: #FFFFFF;
  background: #4CB481;
  border-radius: 100px;  

}

</style>