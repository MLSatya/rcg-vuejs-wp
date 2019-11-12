<template>
    <div class="demo-item-wrapper demo-padding" id="demo_page">
        <div class="demo-items">
            <div class="container">
                <div class="row">
                    <div class="col-md-4 col-sm-6 col-12 mb-50">
                        <div class="demo-item text-center">
                            <router-link target="_blank" :to="{ name: 'Home_one' }">
                                <div class="demo-thumb">
                                    <img src="../../assets/img/demo/preview/home-1.png" alt="Home Version 01">
                                </div>
                                <h2 class="version-title">App Landing 01</h2>
                            </router-link>
                        </div>
                    </div>

                    <div class="col-md-4 col-sm-6 col-12 mb-50">
                        <div class="demo-item text-center">
                            <router-link target="_blank" :to="{ name: 'Home_two' }">
                                <div class="demo-thumb">
                                    <img src="../../assets/img/demo/preview/home-2.png" alt="Home Version 02">
                                </div>
                                <h2 class="version-title">App Landing 02</h2>
                            </router-link>
                        </div>
                    </div>

                    <div class="col-md-4 col-sm-6 col-12 mb-50">
                        <div class="demo-item text-center">
                            <router-link target="_blank" :to="{ name: 'Home_three' }">
                                <div class="demo-thumb">
                                    <img src="../../assets/img/demo/preview/home-3.png" alt="Home Version 03">
                                </div>
                                <h2 class="version-title">App Landing 03</h2>
                            </router-link>
                        </div>
                    </div>

                    <div class="col-md-4 col-sm-6 col-12 mb-50">
                        <div class="demo-item text-center">
                            <router-link target="_blank" :to="{ name: 'Home_four' }">
                                <div class="demo-thumb">
                                    <img src="../../assets/img/demo/preview/home-4.png" alt="Home Version 04">
                                </div>
                                <h2 class="version-title">App Landing 04</h2>
                            </router-link>
                        </div>
                    </div>
                    
                    <div class="col-md-4 col-sm-6 col-12 mb-50">
                        <div class="demo-item text-center">
                            <router-link target="_blank" :to="{ name: 'Home_five' }">
                                <div class="demo-thumb">
                                    <img src="../../assets/img/demo/preview/home-5.png" alt="Home Version 05">
                                </div>
                                <h2 class="version-title">Medical Landing</h2>
                            </router-link>
                        </div>
                    </div>

                    <div class="col-md-4 col-sm-6 col-12 mb-50">
                        <div class="demo-item text-center">
                            <router-link target="_blank" :to="{ name: 'Coming_soon' }">
                                <div class="demo-thumb">
                                    <img src="../../assets/img/demo/preview/coming-soon.png" alt="coming soon">
                                </div>
                                <h2 class="version-title">Coming Soon Landing</h2>
                            </router-link>
                        </div>
                    </div>

                    <div class="col-md-4 col-sm-6 col-12 mb-50">
                        <div class="demo-item text-center">
                            <router-link target="_blank" :to="{ name: 'NotFound' }">
                                <div class="demo-thumb">
                                    <img src="../../assets/img/demo/preview/404.png" alt="404 page">
                                </div>
                                <h2 class="version-title">404 Not Found</h2>
                            </router-link>
                        </div>
                    </div>

                    <div class="col-md-4 col-sm-6 col-12 mb-50">
                        <div class="demo-item text-center">
                            <div class="demo-thumb coming-soon">
                                <img src="../../assets/img/demo/preview/home-6.png" alt="Coming Soon">
                            </div>
                            <h2 class="version-title">Coming Soon</h2>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'DemoItems'
    }
</script>
