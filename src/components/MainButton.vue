<template>
<div class="container">
    <div class="row">
        <div class="col-12">
            <div class="download-app">
                <img class="appstore" src="../assets/appstore.svg" alt="appstore"/>
                <img class="google-play" src="../assets/googleplay.svg" alt="google-play"/>
            </div>
        </div>

        <div class="img3-wrapper">
            <img class="img3" src="../assets/shola.png" alt="shola"/>
        </div>
        <div class="img4-wrapper">
            <img class="img4" src="../assets/moe.png" alt="moe"/>
        </div>
    </div>
</div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .download-app {
        display: flex;
        flex-direction: row;
        justify-content: center;
        margin-bottom: 30px;
    }
    .appstore, .google-play {
        padding: 20px;
        margin-top: 30px;
        cursor: pointer;
    }

    .img3 {
        position: absolute;
        left: 0;
        margin-left: 120px;
        padding: 40px;
    }

     .img4 {
        position: absolute;
        right: 0;
        margin-right: 120px;
        padding: 40px;
    }

</style>