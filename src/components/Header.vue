<script setup>

import { ref, onMounted } from 'vue'

</script>

<template>

<!-- Spinner Start --
<div id="spinner" class="show bg-white position-fixed translate-middle w-100 vh-100 top-50 start-50 d-flex align-items-center justify-content-center">
    <div class="spinner-grow text-primary" style="width: 3rem; height: 3rem;" role="status">
        <span class="sr-only">Loading...</span>
    </div>
</div>
<-- Spinner End -->


<!-- Navbar & Hero Start -->
<div class="container-xxl position-relative p-0" id="home">
    <nav class="navbar navbar-expand-lg navbar-light px-4 px-lg-5 py-3 py-lg-0">
        <a href="" class="navbar-brand p-0">
            <h1 class="m-0">FitApp</h1>
            <!-- <img src="../assets/img/logo.png" alt="Logo"> -->
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse">
            <span class="fa fa-bars"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarCollapse">
            <div class="navbar-nav mx-auto py-0">
                <a href="#home" class="nav-item nav-link active">Home</a>
                <a href="#about" class="nav-item nav-link">About</a>
                <a href="#feature" class="nav-item nav-link">Feature</a>
                <a href="#pricing" class="nav-item nav-link">Pricing</a>
                <!-- <a href="#review" class="nav-item nav-link">Review</a> -->
                <a href="#contact" class="nav-item nav-link">Contact</a>
            </div>
            <a href="" class="btn btn-primary-gradient rounded-pill py-2 px-4 ms-3 d-none d-lg-block">Start Free Trial</a>
        </div>
    </nav>

    <div class="container-xxl bg-primary hero-header">
        <div class="container px-lg-5">
            <div class="row g-5">
                <div class="col-lg-8 text-center text-lg-start">
                    <h1 class="text-white mb-4 animated slideInDown">The Revolutionary App That Helps To Control Your Own Fitness</h1>
                    <p class="text-white pb-3 animated slideInDown">Tempor rebum no at dolore lorem clita rebum rebum ipsum rebum stet dolor sed justo kasd. Ut dolor sed magna dolor sea diam. Sit diam sit justo amet ipsum vero ipsum clita lorem</p>
                    <a href="" class="btn btn-primary-gradient py-sm-3 px-4 px-sm-5 rounded-pill me-3 animated slideInLeft">Read More</a>
                    <a href="" class="btn btn-secondary-gradient py-sm-3 px-4 px-sm-5 rounded-pill animated slideInRight">Contact Us</a>
                </div>
                <div class="col-lg-4 d-flex justify-content-center justify-content-lg-end wow fadeInUp" data-wow-delay="0.3s">
                    <div class="owl-carousel screenshot-carousel">
                        <img class="img-fluid" src="../assets/../assets/img/screenshot-1.png" alt="">
                        <img class="img-fluid" src="../assets/img/screenshot-2.png" alt="">
                        <img class="img-fluid" src="../assets/img/screenshot-3.png" alt="">
                        <img class="img-fluid" src="../assets/img/screenshot-4.png" alt="">
                        <img class="img-fluid" src="../assets/img/screenshot-5.png" alt="">
                    </div>

                    <div class="screenshot-carousel">
                    <img class="img-fluid wow fadeInUp" data-wow-delay="0.5s" src="../assets/img/screenshot-2.png">
                    </div>

                </div>
            </div>
        </div>
    </div>
</div>
<!-- Navbar & Hero End -->


</template>

<style scoped>

</style>
