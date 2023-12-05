<script>
export default {
    data() {
        return {

        }
    }
}
</script>

<template>
    <section>
        <div class="container p-5 ">
            <div class="row row-cols-2">
                <!-- Info -->
                <div class="col">
                    <h2>Get tips tricks on how to skyrocket your sales</h2>
                    <p class="mt-3">Faff about only a quid blower I don't want no agro bleeding chimney pot burke tosser
                        cras nice one boot fanny!</p>
                    <!-- Cards -->
                    <div class="card-report p-3 mt-5 mb-2">
                        <div class="d-flex">
                            <div class="d-flex mt-4">
                                <img class="report" src="../assets/img/510.png" alt="">
                            </div>
                            <div class="ms-4">
                                <h5 class="mb-3">Reporting Analysis</h5>
                                <p>It is a long established fact that a reader will be distracted by the reddable content of
                                    a page when looking at its layout</p>
                            </div>
                        </div>
                    </div>

                    <div class="card-report p-3">
                        <div class="d-flex">
                            <div class="d-flex mt-4">
                                <img class="report" src="../assets/img/511.png" alt="">
                            </div>
                            <div class="ms-4">
                                <h5 class="mb-3">Techinacal SEO Audit</h5>
                                <p>It is a long established fact that a reader will be distracted by the reddable content of
                                    a page when looking at its layout</p>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- Image -->
                <div class="col">
                    <img class="img-tips" src="../assets/img/509.jpeg" alt="">
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
.container {
    margin-top: 40px;
}

p {
    color: hsl(204.71deg 8.13% 59.02%);
}

.col {
    .img-tips {
        position: relative;
        bottom: 10px;
    }
}

.report {
    align-self: self-start;
}

.card-report {
    &:hover {
        h5 {
            color: hsl(219deg 100% 60.78%);
        }

        border-radius: 4px;
        background: #fff;
        box-shadow: 0 6px 10px rgba(0, 0, 0, .08),
        0 0 6px rgba(0, 0, 0, .05);
        transition: .3s transform cubic-bezier(.155, 1.105, .295, 1.12),
        .3s box-shadow,
        .3s -webkit-transform cubic-bezier(.155, 1.105, .295, 1.12);
        cursor: pointer;
        transform: scale(1.05);
        box-shadow: 0 10px 20px rgba(0, 0, 0, .12),
        0 4px 8px rgba(0, 0, 0, .06);
    }
}
</style>