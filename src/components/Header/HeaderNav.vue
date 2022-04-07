<template>
    <div>
        <div class="header">
          <div class="header-nav">
              <div class="header-info">
                <div class="header-info-wrap">
                  <div class="line">
                  </div>

                  <div class="header-info-title">
                      <h1>Title Of The Page</h1>
                  </div>
                    <div class="header-info-deskription">
                      <span>Subtitle</span>
                      <div class="info-deskription-text">
                      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam pharetra turpis tristique nisi laoreet gravida. Sed sed orci ut ante pellentesque efficitur id ac erat. Morbi metus metus, dictum sed arcu at, interdum porttitor erat.
                      </p>
                      </div>

                      <button>BUTTON</button>
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
.header {
  max-width: 850px;
  width: 100%;
  height: 835px;
  margin:0 auto;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 5px;
}
.header-nav {
  max-width:800px;
  width: 100%;
  height:460px;
  margin: 0 auto;
  display: flex;
  justify-content: flex-end;
}

.header-info {
     max-width: 795px;
    width: 100%;
    display: flex;
}
.header-info-wrap {
  max-width:815px;
  width: 100%;
  height:459px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;

}
.line {
  width: 60px;
  height: 4px;
  background: #4CB481;
  border-radius: 2px;
  margin-top:20px;
}
.header-info-title {
  max-width:800px;
  width: 100%;
  height:95px;
  display: flex;
  justify-content: flex-start;
  align-items: center;
  
}
.header-info-title>h1{
  font-family: 'Poppins', sans-serif;
  line-height: 60px;
  font-size: 62px;
  font-style: normal;
  font-weight: 600;
  line-height: 93px;
  text-transform: uppercase;
  color: #FFFFFF;
}

.header-info-deskription>span{
font-family: 'Poppins', sans-serif;
font-style: normal;
font-weight: 500;
font-size: 30px;
line-height: 75px;
text-transform: uppercase;
color: #FFFFFF;
}

.header-info-deskription{
  max-width: 790px;
  width:100%;
  height:330px;
  display: block;
  text-align:left;

}
.info-deskription-text {
  max-width: 790px;
  width:100%;
  height: 180px;
  display:flex;

}
.info-deskription-text>p{
  font-family: 'Poppins', sans-serif;
  font-style: normal;
  font-weight: 300;
  font-size: 22px;
  line-height: 36px;
  color: rgba(255, 255, 255, 0.5);
}
.header-info-deskription>button{
  margin-top: 10px;
   font-family: 'Poppins', sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 20px;
  line-height: 36px;
  max-width:200px;
  width: 100%;
  height: 60px;
  border: none;
  text-align: center;
  text-transform: uppercase;
  color: #FFFFFF;
  background: #4CB481;
  border-radius: 100px;
  cursor: pointer;
}
</style>
