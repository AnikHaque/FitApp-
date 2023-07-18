<script setup>

import { ref, onMounted } from 'vue'

</script>

<template>

<!-- Pricing Start -->
<div class="container-xxl py-5" id="pricing">
    <div class="container py-5 px-lg-5">
        <div class="text-center wow fadeInUp" data-wow-delay="0.1s">
            <h5 class="text-primary-gradient fw-medium">Pricing Plan</h5>
            <h1 class="mb-5">Choose Your Plan</h1>
        </div>
        <div class="tab-class text-center pricing wow fadeInUp" data-wow-delay="0.1s">
            <ul class="nav nav-pills d-inline-flex justify-content-center bg-primary-gradient rounded-pill mb-5">
                <li class="nav-item">
                    <button class="nav-link active" data-bs-toggle="pill" href="#tab-1">Monthly</button>
                </li>
                <li class="nav-item">
                    <button class="nav-link" data-bs-toggle="pill" href="#tab-2">Yearly</button>
                </li>
            </ul>
            <div class="tab-content text-start">
                <div id="tab-1" class="tab-pane fade show p-0 active">
                    <div class="row g-4">
                        <div class="col-lg-4">
                            <div class="bg-light rounded">
                                <div class="border-bottom p-4 mb-4">
                                    <h4 class="text-primary-gradient mb-1">Starter Plan</h4>
                                    <span>Powerful & Awesome Features</span>
                                </div>
                                <div class="p-4 pt-0">
                                    <h1 class="mb-3">
                                        <small class="align-top" style="font-size: 22px; line-height: 45px;">$</small>14.99<small
                                            class="align-bottom" style="font-size: 16px; line-height: 40px;">/ Month</small>
                                    </h1>
                                    <div class="d-flex justify-content-between mb-3"><span>HTML5 & CSS3</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <div class="d-flex justify-content-between mb-3"><span>Bootstrap v5</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <div class="d-flex justify-content-between mb-3"><span>Responsive Layout</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <div class="d-flex justify-content-between mb-2"><span>Cross-browser Support</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <a href="" class="btn btn-primary-gradient rounded-pill py-2 px-4 mt-4">Get Started</a>
                                </div>
                            </div>
                        </div>
                        <div class="col-lg-4">
                            <div class="bg-light rounded border">
                                <div class="border-bottom p-4 mb-4">
                                    <h4 class="text-primary-gradient mb-1">Advance Plan</h4>
                                    <span>Powerful & Awesome Features</span>
                                </div>
                                <div class="p-4 pt-0">
                                    <h1 class="mb-3">
                                        <small class="align-top" style="font-size: 22px; line-height: 45px;">$</small>24.99<small
                                            class="align-bottom" style="font-size: 16px; line-height: 40px;">/ Month</small>
                                    </h1>
                                    <div class="d-flex justify-content-between mb-3"><span>HTML5 & CSS3</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <div class="d-flex justify-content-between mb-3"><span>Bootstrap v5</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <div class="d-flex justify-content-between mb-3"><span>Responsive Layout</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <div class="d-flex justify-content-between mb-2"><span>Cross-browser Support</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <a href="" class="btn btn-secondary-gradient rounded-pill py-2 px-4 mt-4">Get Started</a>
                                </div>
                            </div>
                        </div>
                        <div class="col-lg-4">
                            <div class="bg-light rounded">
                                <div class="border-bottom p-4 mb-4">
                                    <h4 class="text-primary-gradient mb-1">Premium Plan</h4>
                                    <span>Powerful & Awesome Features</span>
                                </div>
                                <div class="p-4 pt-0">
                                    <h1 class="mb-3">
                                        <small class="align-top" style="font-size: 22px; line-height: 45px;">$</small>34.99<small
                                            class="align-bottom" style="font-size: 16px; line-height: 40px;">/ Month</small>
                                    </h1>
                                    <div class="d-flex justify-content-between mb-3"><span>HTML5 & CSS3</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <div class="d-flex justify-content-between mb-3"><span>Bootstrap v5</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <div class="d-flex justify-content-between mb-3"><span>Responsive Layout</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <div class="d-flex justify-content-between mb-2"><span>Cross-browser Support</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <a href="" class="btn btn-primary-gradient rounded-pill py-2 px-4 mt-4">Get Started</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div id="tab-2" class="tab-pane fade p-0">
                    <div class="row g-4">
                        <div class="col-lg-4">
                            <div class="bg-light rounded">
                                <div class="border-bottom p-4 mb-4">
                                    <h4 class="text-primary-gradient mb-1">Starter Plan</h4>
                                    <span>Powerful & Awesome Features</span>
                                </div>
                                <div class="p-4 pt-0">
                                    <h1 class="mb-3">
                                        <small class="align-top" style="font-size: 22px; line-height: 45px;">$</small>114.99<small
                                            class="align-bottom" style="font-size: 16px; line-height: 40px;">/ Yearly</small>
                                    </h1>
                                    <div class="d-flex justify-content-between mb-3"><span>HTML5 & CSS3</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <div class="d-flex justify-content-between mb-3"><span>Bootstrap v5</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <div class="d-flex justify-content-between mb-3"><span>Responsive Layout</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <div class="d-flex justify-content-between mb-2"><span>Cross-browser Support</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <a href="" class="btn btn-primary-gradient rounded-pill py-2 px-4 mt-4">Get Started</a>
                                </div>
                            </div>
                        </div>
                        <div class="col-lg-4">
                            <div class="bg-light rounded border">
                                <div class="border-bottom p-4 mb-4">
                                    <h4 class="text-primary-gradient mb-1">Advance Plan</h4>
                                    <span>Powerful & Awesome Features</span>
                                </div>
                                <div class="p-4 pt-0">
                                    <h1 class="mb-3">
                                        <small class="align-top" style="font-size: 22px; line-height: 45px;">$</small>124.99<small
                                            class="align-bottom" style="font-size: 16px; line-height: 40px;">/ Yearly</small>
                                    </h1>
                                    <div class="d-flex justify-content-between mb-3"><span>HTML5 & CSS3</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <div class="d-flex justify-content-between mb-3"><span>Bootstrap v5</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <div class="d-flex justify-content-between mb-3"><span>Responsive Layout</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <div class="d-flex justify-content-between mb-2"><span>Cross-browser Support</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <a href="" class="btn btn-primary-gradient rounded-pill py-2 px-4 mt-4">Get Started</a>
                                </div>
                            </div>
                        </div>
                        <div class="col-lg-4">
                            <div class="bg-light rounded">
                                <div class="border-bottom p-4 mb-4">
                                    <h4 class="text-primary-gradient mb-1">Premium Plan</h4>
                                    <span>Powerful & Awesome Features</span>
                                </div>
                                <div class="p-4 pt-0">
                                    <h1 class="mb-3">
                                        <small class="align-top" style="font-size: 22px; line-height: 45px;">$</small>134.99<small
                                            class="align-bottom" style="font-size: 16px; line-height: 40px;">/ Yearly</small>
                                    </h1>
                                    <div class="d-flex justify-content-between mb-3"><span>HTML5 & CSS3</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <div class="d-flex justify-content-between mb-3"><span>Bootstrap v5</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <div class="d-flex justify-content-between mb-3"><span>Responsive Layout</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <div class="d-flex justify-content-between mb-2"><span>Cross-browser Support</span><i class="fa fa-check text-primary-gradient pt-1"></i></div>
                                    <a href="" class="btn btn-primary-gradient rounded-pill py-2 px-4 mt-4">Get Started</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
<!-- Pricing End -->


</template>

<style scoped>

</style>
