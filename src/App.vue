<template>
<div id="app">
  <div class="nav-menu">
              <div class="nav-menu-list">
                  <div class="menu-list-logo">
                      <a href="#">SDS</a>
                  </div>
                  <div class="list-menu-item">

                      <div class="item-link">
                        <a href="#">Work</a>
                      </div>
                       <div class="item-link">
                        <a href="#">About</a>
                      </div>
                       <div class="item-link">
                        <a href="#">Services</a>
                      </div>
                       <div class="item-link">
                        <a href="#">blog</a>
                      </div>
                       <div class="item-link">
                        <a href="#">Contact</a>
                      </div>
                  </div>
                    <div class="search-form">
                        <a href="#"><img src="@/assets/search.svg" title="logo"/></a>
                    </div>
              </div>
            </div> 

    <div class="page">
    <HeaderNav />
    <ContentBlock />
      <FooterNav />
    </div>

</div>
</template>

<script>
import HeaderNav from './components/Header/HeaderNav.vue'
import FooterNav from './components/Footer/FooterNav.vue'
import ContentBlock from './components/Сontent/ContentBlock.vue'

export default {
 components: {
   HeaderNav,
   FooterNav,
   ContentBlock,
 }

  
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #d2dae2;
  background: #282D31;
  max-width: 1600px;
  width: 100%;
  display: flex;
  margin: 0 auto; 
}

*,
*:before,
*:after {
    box-sizing: border-box;
}

h1, h2, h3, h4, h5, h6 {
    margin: 0;
}
a {
  text-decoration: none;
}
p {
    margin: 0 0 10px;
}
body {
  margin: 0;
  padding: 0;
}
button {
  border: none;
}

ul, ol {
    margin: 0;
    padding: 0;
    list-style: none;
}
.nav-menu {
  max-width: 150px;
  width: 100%;
  display: flex;
  flex-direction: column;
  left: 0;
  height: 100%;

}
.page {
  max-width: 1980px;
  width: 100%;
  display: flex;
  flex-direction: column;
 
}

.nav-menu-list  {
    max-width: 150px;
  width: 100%;
   height: 560px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
 

}
.menu-list-logo  {
   max-width: 150px;
   width: 100%;
   height: 140px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.menu-list-logo>a{
  font-family: 'Sawarabi Gothic', sans-serif;
  font-style: normal;
  font-weight: 400;
  font-size: 32px;
  line-height: 55px;
  color:#4CB481;
  display: flex;
  flex-direction: column;
  justify-content: center;
  text-align: center;

}
.menu-list-logo>a::after{
  content: '';
  width: 25px;
  height: 4px;
  background: #4CB481;
  border-radius: 2px;
  margin: 0 auto;
}
.list-menu-item  {
  max-width: 90px;
  width: 100%;
   height: 320px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  border-top:2px solid #3E4146;
  border-bottom:2px solid #3E4146; 
}
.item-link  {
  max-width: 90px;
  width: 100%;
  height: 50px;
  display: flex;
  align-items: center;
  justify-content: center;

}
.item-link>a{
  font-family: 'Poppins', sans-serif;
  font-size: 16px;
  font-style: normal;
  font-weight: 600;
  line-height: 24px;
  text-transform: uppercase;
  color: rgba(255, 255, 255, 0.5);

}
.search-form  {
  max-width: 150px;
  width: 100%;
  height: 70px;
  display: flex;
  flex-direction: column;
  justify-content: flex-end;

}

   @media (max-width: 1380px) {
      .block-cart-wrap {
        padding: 0 5px;
    }
    .from-blog {
      margin: 10px 5px;
    }
    .form-blog-deskription {
      margin: 0 10px;
    }
    .social-network {
      justify-content: center;
    }
    
   }

    @media (max-width: 1280px) {
       .info-deskription-text {
        padding: 0 5px;
        height: auto;
      }
      .block-cart-item {
        height: auto;
        flex-wrap: wrap;
        justify-content: center;
        margin: 50px auto;
    }
    .item-cart-wrap {
        margin: 50px auto;
    }
    .form-desk-text {
      height: auto;
    }

    .block-quote-wrap {
      padding: 0 15px;
    }
    .footer-nav {
    align-items: center;
    flex-direction: column;
    }
    .footer-list-link {
    height: 120px;
    }
    .social-network {
      justify-content: center;
    }

   }

     @media (max-width: 850px) {
       .from-blog {
         height: auto;
       }
       .from-blog-wrpaer{
         height: auto;
       }
       .form-blog-item {
         flex-direction: column;
             align-items: center;
       }
       .from-blog-title {
         margin: 0 auto;
         height: auto;
       }
       .form-blog-img>img {
         margin: 0 10px;
       }
       .block-quote-text {
        height: auto;
     }
     }
    @media (max-width: 720px) {
      .header-info-title {
        justify-content: center;
      }
      .header-info-title>h1 {
      font-size: 53px;
      }
      .header-info-deskription {
          text-align: center;
      }
      .form-blog-img {
      margin: 0 auto;
      padding: 0 5px;
    }
    .footer-nav { 
      flex-direction: row;
    }
    .footer-list-link>ul {
      height: auto;
      flex-direction: column;
    }
    .footer-list-link {
      height: auto;
    }

    }
      @media (max-width: 650px) {
        .line {
      display: none;
    }
     #app {
      flex-direction: column;
    }
    .header {
    margin: 5px auto;
    height: auto;
    }
    .nav-menu {
      max-width: 650px;
      flex-direction: row;
    }
    .header-nav {
      height: auto;
    }
    .header-info-wrap {
      margin: 10px auto;
      height: auto;
    }
    .nav-menu-list {
      max-width: 650px;
      height: auto;
    }
    .list-menu-item {
      flex-direction: row;
      height: auto;
      max-width: 480px;
      border-top:0;
      border-bottom: 0;
    }
    
      .header-info-title>h1 {
        font-size: 46px;
        text-align: center;
        line-height: 50px;
      }
      .block-quote {
        height: auto;
      }
      .block-quote-wrap {
        height: auto;
        margin: 5px auto;
      }
    .form-blog-deskription {
    
    align-items: center;
    text-align: center;
    }
    .form-desk-title {
    justify-content: center;
    }
    .form-desk-text {
    justify-content: center;
    text-align: center;
    }
    .form-blog-item {
      margin-top: 10px;
    }

    
}

@media (max-width: 375px) { 
    .list-menu-item {
      flex-direction:column;
      align-items: center;
    }
    .header-info-deskription {
      height: auto;
    }
    .list-menu-item {
          max-width: 85px;
      border-top: 2px solid #3E4146;
    border-bottom: 2px solid #3E4146;
    }
    .from-blog-title>h2 {
      font-size: 40px;
    }
}


</style>
