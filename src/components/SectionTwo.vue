<template>
    <div class="container">
        <div class="row content-wrapper">
            <div class="col-6">
                    <img class="image1" src="../assets/image2.png" alt="image"/>
            </div>
            <div class="col-6 texts">
                <h3 class="header-text">You have <span class="inspire">zero </span>chances of not<br/> being replied. <br/></h3>
                <p class="text">Sending a DM should no more be an issue of shooting your shot or trying<br/> your luck. You’re paying, so you’re definitely going to get a response,<br/> and not just a response, but a conversation.</p>
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
        margin-top: 140px;
        margin-bottom: 20px;
    }

    .header-text {
        color:  #39393F;
        font-weight: 600;
        text-align: left;
        margin-top: 100px;
        line-height: 46.88px;
    }

    .inspire {
        font-style: italic;
        color: #00BF69;
    }

    .text {
        font-size: 12px;
        text-align: left;
        margin-top: 20px;
    }

    .texts {
        margin-right: -160px;
    }

    .content-wrapper {
        display: flex;
        justify-content: space-around;
        padding: 40px;
    }

    .image1 {
        margin-left: -160px;
    }
    

</style>