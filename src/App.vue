<template>
    <div id="app" class="main-content" style="height: 100vh">
        <div class="container">
            <div class="row">
                <div class="d-flex justify-content-center align-items-center my-5">
                    <!-- card -->
                    <div
                        class="card align-items-center col-sm-10 col-md-8 col-lg-6 col-xl-4 shadow-lg super-rounded img-fluid"
                    >
                        <img src="./assets/illustration-hero.svg" alt="" class="card-img-top" />

                        <div class="card-body px-5">
                            <!-- title -->
                            <h1 class="card-title text-center mt-4">Order Summary</h1>

                            <!-- text -->
                            <p class="card-text text-center text-secondary my-3">
                                You can now listen to millions of songs, audiobooks, and podcasts on
                                any device anywhere you like!
                            </p>

                            <!-- summary info -->
                            <div
                                class="p-4 my-4 bg-light rounded d-flex align-items-center justify-content-around"
                            >
                                <!-- icon -->

                                <div class="mr-2">
                                    <img src="./assets/icon-music.svg" height="50px" width="50px" />
                                </div>

                                <!-- payment summary -->

                                <div class="align-items-center">
                                    <h6 class="small p-0">Annual Plan</h6>

                                    <p class="text-muted small align-self-bottom">$59.99/year</p>
                                </div>

                                <!-- change plan button -->

                                <button class="btn btn-link btn-sm fw-bold">Change</button>
                            </div>

                            <div class="d-grid gap-2 d-block">
                                <!-- pay button -->

                                <button class="btn btn-primary btn-lg shadow-lg">
                                    Proceed to Payment
                                </button>

                                <!-- cancel button  -->

                                <button
                                    class="btn btn-link text-secondary fw-bold"
                                    style="text-decoration: none"
                                >
                                    Cancel Order
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "App",
};
</script>

<style>
#app {
    background-color: #e0e8ff;
}

.btn-primary {
    background-color: #3829e0;
    border-radius: 10px;
    border: 0;
}

.btn-link {
    color: #3829e0;
}

.super-rounded {
    border-radius: 25px;
}

.card-img-top {
    border-top-left-radius: 25px;
    border-top-right-radius: 25px;
}
</style>
