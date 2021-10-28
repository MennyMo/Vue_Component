<template>
<nav class="navbar navbar-expand-lg">
  <div class="container">
    <a class="navbar-brand" href="#">
        <img src="../assets/logo.svg" alt="logo"/>
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav nav-links">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">{{ about }}</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">{{ faq }}</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">{{ contact }}</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>

<script>
export default {
  data () {
    return {
      about: 'About',
      faq: 'FAQs',
      contact: 'Contact us'
    }
  }
}
</script>

<style scoped>
    .nav-links {
        justify-items: right;
        font-size: 12px;
        margin-left: auto;
    }
    .nav-link {
        color:#6A6A70;
        margin-left: 40px;
    }
</style>
