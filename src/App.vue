<template>
  <v-app>
    <v-main>
      <div class="main-content-container">
        <div class="main-contnet">
          <div class="header">
            <h1 class="main-header">yanni's</h1>
            <div class="main-header2">ice cream</div>
          </div>
          <div class="description-container">
            <div class="img-banner">
                <div class="cool-text">better ice cream</div>
                <div class="cool-text">handmade</div>
                <div class="cool-text">grassfed dairy</div>
                <div class="cool-text">delicious</div>
                <v-btn class="order-now">order now</v-btn>
            </div>
          </div>
          <div class="description-container2">
            <div class="img-banner">
                <div class="cool-text">better ice cream</div>
                <div class="cool-text">handmade</div>
                <div class="cool-text">grassfed dairy</div>
                <div class="cool-text">delicious</div>
                <v-btn class="order-now">order now</v-btn>
            </div>
          </div>
            <!-- <div class="description-box">
              <img class="photo" :src="require('./assets/photos/corn-blackberry.jpg')"/>
              <div class="cool-text-box">
                <div class="cool-text">better ice cream</div>
                <div class="cool-text">handmade</div>
                <div class="cool-text">grassfed dairy</div>
                <div class="cool-text">delicious</div>
                <v-btn class="order-now">order now</v-btn>
              </div>
            </div>
             <div class="description-box">
        
              <div class="cool-text-box">
                <div class="cool-text">better ice cream</div>
                <div class="cool-text">handmade</div>
                <div class="cool-text">grassfed dairy</div>
                <div class="cool-text">delicious</div>
                <v-btn class="order-now">order now</v-btn>
              </div>
              <img class="photo" :src="require('./assets/photos/scoop.jpg')"/>
            </div> -->

          <!-- </div> -->

        </div>
      </div>
    </v-main>
  </v-app>
</template>

<script>

// import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',
  // components: {HelloWorld},

  data: () => ({
    //
  }),
};
</script>

<style scoped>
.main-content-container {
  background:#aed2d4;
  width: 100%;
  height: 100%;
}

.main-contnet {
  width: 900px;
  max-width: 100%;
  height:100%;
  background: white;
  margin: 0 auto;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}

.header {
  padding-top:60px;
}

.main-header {
  text-align: center;
    font-size: 94px;
    line-height: 48px;
    font-family: Calistoga;
    color: #e46454;
    font-weight: normal;
}

.main-header2 {
  text-align: center;
    font-size: 50px;
    font-family: Calistoga;
    color: #aed2d4;
}

.description-box {
  display: flex;
  /* margin-right: 16px; */
  margin-top: 24px;
  /* margin-left:16px; */
} 

.img-banner {
      width: 454px;
    margin-top: 24px;
    margin-bottom: 24px;
    padding: 24px;
    background: white;
    background-color: rgba(255, 255, 255, 0.8);
    text-align: center;
    }

.img-banner:after{
    opacity:0.5;
}

.img-banner2 {
      width: 454px;
    margin-top: 24px;
    margin-bottom: 24px;
    padding: 24px;
    background: white;
    background-color: rgba(255, 255, 255, 0.8);
    text-align: center;
    }

.photo {
  width: 100%;
}

.description-container {
  margin-top: 24px;
    background: url(/img/corn-blackberry.4440df92.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    justify-content: center;
    display: flex;
}

.description-container2 {
  margin-top: 24px;
    background: url(/assets/photos/mex-hc.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    display: flex;
}


.cool-text-box {
  margin-left: 24px;
  margin-right: 24px;
}

.cool-text {
  font-family: Calistoga;
  font-size: 50px;
  color: #666;
}

.order-now {
          background-color: rgb(228, 100, 84) !important;
    border-color: rgb(228, 100, 84);
    font-family: Calistoga;
    color: white !important;
    font-size: 50px !important;
    padding-top: 32px !important;
    /* width: 90% !important; */
    text-transform: lowercase;
    /* margin-right: 50% !important; */
    /* margin-left: 50%; */
    /* justify-content: center; */
    /* align-items: center; */
    padding-bottom: 32px !important;
}


.uhh {
  position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    padding:32px;
    background: white;
    border-radius: 5px;
    opacity: 0.85;


}




</style>
