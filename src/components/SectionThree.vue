<template>
    <div class="container text-center">
        <div class="row content-wrapper">
            <div class="col-12">
                    <img class="image1" src="../assets/image3.png" alt="image"/>
            </div>
            <div class="col-12 texts">
                <h3 class="header-text">There’s no <span class="inspire">better way </span>of reaching<br/> out to those who inspires you</h3>
                <p class="text">Ear1 lets influencers charge you a small fee to have a conversation with them. Being required to<br/> pay filters out all the unserious people so your favourite influencers can respond to you faster.</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data () {
        return {
            
        }
    }
}
</script>

<style scoped>

    .container {
        display: flex;
        margin-top: 140px;
        margin-bottom: 20px;
        justify-content: center;
    }

    .header-text {
        color:  #39393F;
        font-weight: 600;
        text-align: center;
        margin-top: 100px;
        line-height: 46.88px;
    }

    .inspire {
        font-style: italic;
        color: #00BF69;
    }

    .text {
        font-size: 12px;
        text-align: center;
        margin-top: 20px;
    }

    .content-wrapper {
        display: flex;
        flex-direction: column;
    }

</style>