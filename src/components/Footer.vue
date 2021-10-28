<template>
  <div class="footer">
      <div class="content">
      <div >
          <img src="../assets/logo-footer.svg" alt="logo" id="ear1"/>

              <p>2020 ear1Social</p>
              <p>Privacy policy | Terms of service</p>
          </div>
          <div>
              <ul>
                  <li> {{company}} </li>
                  <li> {{about}} </li>
                  <li>{{questions}}</li>
                  <li>{{ask}}</li>
              </ul>
          </div>
          <div>
              <ul>
                  <li>Get in Touch</li>
                  <li>Questions or feedback?, we <br> would love to hear from you. </li>
                  <li id="img">
                     <img src="../assets/fb.svg" alt="facebook">
                      <img src="../assets/twitter.svg" alt="twitter">
                      <img src="../assets/ig.svg" alt="instagram"></li>
              </ul>
          </div>
  </div>
      <!-- <slot name="name">Molly</slot> -->

  </div>
  
</template>

<script>
export default {
    data(){
        return {
            company: 'COmpany',
            about: 'About Us',
            questions: 'FAQs',
            ask: 'Contact Us'
        }
    },
    methods: {
        
    }

}
</script>

<style>
    .footer{
        background: black;
        color: white;
        line-height: 50px;
        background: #39393F;
    }
    
    li{
        list-style: none;
    }
    .content{
        margin-top: 50px;
        padding: 3rem;
        display: flex;
        justify-content: space-between;
    }
    img {
        padding: 5px;
    }
  
</style>