<template>
  <div>
        <div class="img1-wrapper">
            <img class="img1" src="../assets/davido.png" alt="davido"/>
        </div>
         <div class="img2-wrapper">
            <img class="img2" src="../assets/propser.png" alt="propser"/>
        </div>
      <div>
            <h1 class="main-heading">Connect with professionals in your<br/> field without getting aired.</h1>
            <p class="main-text">For a small fee, ear1 allows you to get in touch with professionals in your<br/> field and build quality relationships with them. </p>
      </div>
      
  </div>
</template>

<script>
export default {
    data() {
        return {
            
        }
    }
}
</script>

<style scoped>
    .main-heading {
        font-size: 30px;
        text-align: center;
        margin-top: 60px;
        font-weight: 600;
        line-height: 48.59px;
    }

    .main-text {
        font-size: 12px;
        color: #6A6A70;
        margin-top: 20px;
    }

    .img1 {
        position: absolute;
        left: 0;
        margin-left: 60px;
        margin-top: 90px;
    }

    .img2 {
        position: absolute;
        right: 0;
        margin-right: 60px;
        margin-top: 60px;
    }
</style>
