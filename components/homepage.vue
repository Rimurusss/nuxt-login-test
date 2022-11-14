<template>
    <div class="container">
      <div>
        <!-- <Logo /> -->
        <h1 class="title">
          CardX Shop
        </h1>
        <div class="links" >
            <v-btn elevation="2" x-large to="/login">เข้าสู่เว็บไซต์</v-btn>
            <!-- <b-button id="buttonhome" size="lg" to="/home">เข้าสู่เว็บไซต์</b-button> -->
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {}
  </script>
  
  <style scoped>
  *{
    margin: 0;
    padding:0;
    box-sizing: border-box;
  }
  .container{
    min-height: 100vh;
    width:100%;
    background-color: #000;
    background-image: url(https://i.pinimg.com/originals/79/a3/84/79a384c3c449ad01b0e57e790807b2c0.gif);
    background-position: center;
    background-repeat: no-repeat;
    background-size: 70;
    color:#fff;
    padding: 0 8%;
  }
  .container {
    margin: 0;
    min-height: 100vh;
    min-width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
  }
  
  /* .title {
    font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
      'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
    display: block;
    font-weight: 300;
    font-size: 100px;
    color: #35495e;
    letter-spacing: 1px;
  } */
  
  /* .subtitle {
    font-weight: 300;
    font-size: 42px;
    color: #526488;
    word-spacing: 5px;
    padding-bottom: 15px;
  } */
  
  .links {
    padding-top: 15px;
    text-align: center;
    display: flex;
    justify-content: center;
  }
  #buttonhome{
    padding: 1rem;
    background-color: #fff;
    color: #000;
  }
  </style>
  