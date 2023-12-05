<script>
export default {
    data() {
        return {
        }
    }
}

</script>

<template>
    <div class="container p-5">
        <!-- Background Image -->
        <img class="bg-circle" src="../assets/img/14.png" alt="">
        <!-- Title and button -->
        <div class="row d-flex align-items-center">
            <div class="col-8">
                <h2>Popular feature that your business needs</h2>
                <p class="mt-3">Faff about only a quid blower I don't want no agro bleeding chimney pot burke tosser cras
                    nice one boot
                    fanny.!</p>
            </div>
            <!-- Button -->
            <div class="col">
                <button type="button" class="btn btn-primary ms-5 p-3">
                    Explore More Feature
                </button>
            </div>
        </div>
        <!-- Cards -->
        <div class="container p-3">
            <div class="row d-flex g-5">
                <!-- Card -->
                <div class="col-md-4 col-xl-3">
                    <div class="card p-3">
                        <div>
                            <h6 class="mb-3">Customized Invoices</h6>
                            <h3 class="text-right">
                                <i class="fa-solid fa-chart-line"></i>
                            </h3>
                        </div>
                    </div>
                </div>

                <!-- Card -->
                <div class="col-md-4 col-xl-3">
                    <div class="card p-3">
                        <div>
                            <h6 class="mb-3">Stock Management</h6>
                            <h3 class="text-right">
                                <i class="fa-regular fa-paper-plane"></i>
                            </h3>
                        </div>
                    </div>
                </div>

                <!-- Card -->
                <div class="col-md-4 col-xl-3">
                    <div class="card p-3">
                        <div>
                            <h6 class="mb-3">Receivable & Payables</h6>
                            <h3 class="text-right">
                                <i class="fa-solid fa-file-invoice-dollar"></i>
                            </h3>
                        </div>
                    </div>
                </div>

                <!-- Card -->
                <div class="col-md-4 col-xl-3">
                    <div class="card p-3">
                        <div>
                            <h6 class="mb-3">Manage Buying</h6>
                            <h3 class="text-right">
                                <i class="fa-solid fa-credit-card"></i>
                            </h3>
                        </div>
                    </div>
                </div>

                <!-- Card -->
                <div class="col-md-4 col-xl-3">
                    <div class="card p-3">
                        <div>
                            <h6 class="mb-3">Powerful & Secure</h6>
                            <h3 class="text-right">
                                <i class="fa-solid fa-file-shield"></i>
                            </h3>
                        </div>
                    </div>
                </div>

                <!-- Card -->
                <div class="col-md-4 col-xl-3">
                    <div class="card p-3">
                        <div>
                            <h6 class="mb-3">Fastest Return Filing</h6>
                            <h3 class="text-right">
                                <i class="fa-solid fa-truck-fast"></i>
                            </h3>
                        </div>
                    </div>
                </div>

                <!-- Card -->
                <div class="col-md-4 col-xl-3">
                    <div class="card p-3">
                        <div>
                            <h6 class="mb-3">Monthly Detailed</h6>
                            <h3 class="text-right">
                                <i class="fa-solid fa-scroll"></i>
                            </h3>
                        </div>
                    </div>
                </div>

                <!-- Card -->
                <div class="col-md-4 col-xl-3">
                    <div class="card p-3">
                        <div>
                            <h6 class="mb-3">Product Management</h6>
                            <h3 class="text-right">
                                <i class="fa-regular fa-thumbs-up"></i>
                            </h3>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.container {
    margin-top: 50px;
}

h2 {
    letter-spacing: 1px;
    margin-bottom: 20px;
}

p {
    color: hsl(204.71deg 8.13% 59.02%);
}

.bg-circle {
    position: absolute;
    left: -500px;
    top: 1700px;
    background-image: url("../assets/img/14.png");
}

.row {
    margin-left: 10px;
}

.card {
    border-radius: 4px;
    background: #fff;
    cursor: pointer;
    transform: scale(1.05);
    box-shadow: 0 10px 20px rgba(0, 0, 0, .12),
        0 4px 8px rgba(0, 0, 0, .06);

    .fa-chart-line {
        color: hsl(219.14deg 100% 63.33%);
    }

    .fa-paper-plane {
        color: hsl(4.93deg 100% 71.37%);
    }

    .fa-file-invoice-dollar {
        color: hsl(166.39deg 59.51% 68.04%);
    }

    .fa-credit-card {
        color: hsl(219.14deg 100% 63.33%);
    }

    .fa-file-shield {
        color: hsl(4.93deg 100% 71.37%);
    }

    .fa-truck-fast {
        color: hsl(166.39deg 59.51% 68.04%);
    }

    .fa-scroll {
        color: hsl(219.14deg 100% 63.33%);
    }

    .fa-thumbs-up {
        color: hsl(4.93deg 100% 71.37%);
    }



    &:hover {
        background-color: rgb(136 225 205);
        color: white;

        .fa-chart-line {
            color: hsl(0, 0%, 100%);
        }

        .fa-paper-plane {
            color: hsl(0, 0%, 100%);
        }

        .fa-file-invoice-dollar {
            color: hsl(0, 0%, 100%);
        }

        .fa-credit-card {
            color: hsl(0, 0%, 100%);
        }

        .fa-file-shield {
            color: hsl(0, 0%, 100%);
        }

        .fa-truck-fast {
            color: hsl(0, 0%, 100%);
        }

        .fa-scroll {
            color: hsl(0, 0%, 100%);
        }

        .fa-thumbs-up {
            color: hsl(0, 0%, 100%);
        }
    }
}
</style>