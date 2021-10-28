<template>
  <div class="container">
      <div class="build">
          <div class="row build">
              <div class="col-6">
                  <h3 class="text-header">Build great relationships with<br/> those you admire.</h3>
                  <p class="texts">With ear1, replies to your DMs are guaranteed!</p>
              </div>
              <div class="col-6 download-app">
                  <img class="app-store" src="../assets/app-store-dark.svg" alt="app-store"/>
                  <img class="google-play" src="../assets/google-play-dark.svg" alt="app-store"/>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {

} 
</script>

<style scoped>
    .container {
        background: #00BF69;
        display: block;
        width: 100%;
        padding: 60px;
        border-radius: 12px;
        margin-top: 100px;
        margin-bottom: 30px;
        justify-content: center;
    }
    .build {
        margin-top: 10px;
    }
    .text-header {
        text-align: left;
        font: 600;
        color: #fff;
        font-size: 24px;
    }
    .texts {
        color: #fff;
        text-align: left;
        font-size: 12px;
    }
    .download-app {
        display: flex;
        align-content: center;
    }
    .app-store {
        margin-right: 20px;
        cursor: pointer;
    }
    .google-play {
        cursor: pointer;
    }
</style>