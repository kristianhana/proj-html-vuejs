<script>
</script>

<template>
    <div class="container">
        <div class="title text-center">
            <h2 class="mb-3">Contact with our team</h2>
            <p>If you are planning on developing a product landing.</p>
        </div>
        <div class="row row-cols-2">
            <!-- Map -->
            <div class="col position-relative">
                <img class="map" src="../assets/img/StaticMapService.GetMapIma.png" alt="">
                <!-- Card -->
                <div class="card p-3">
                    <div class="d-flex">
                        <div>
                            <h5>Storey Ave</h5>
                            <p class="mb-4">San Francisco, California 94129</p>
                            <a href="">Visualizza mappa piu' grande</a>
                        </div>

                        <div class="ms-5">
                            <i class="fa-solid fa-diamond-turn-right fs-3 d-flex mb-2 ms-3" style="color: #4d8eff;"></i>
                            <a href="">Indicazi...</a>
                        </div>
                    </div>
                </div>

                <!-- Plus minus buttons -->
                <div class="plus-minus-btn">
                    <div class="plus">
                        <button class="btn-plus">
                            <i class="fa-solid fa-plus"></i>
                        </button>
                    </div>
                    <div class="minus">
                        <button class="btn-minus">
                            <i class="fa-solid fa-minus"></i>
                        </button>
                    </div>
                </div>

                <!-- Map ping -->
                <div>
                   <img class="ping" src="../assets/img/pin.png.png" alt="">
                </div>

                <!-- Image mountain -->
                <div>
                    <img class="mountain" src="../assets/img/montain.png.jpg" alt="">
                </div>

                <!-- Info -->
                <div class="d-flex badges">
                      <div class="badge">
                        <p>Dati mappa ©2020 </p>
                      </div>

                      <div class="badge">
                        <p>Termini e condizioni d'uso</p>
                      </div>

                      <div class="badge">
                        <p>Segnala un errore nella mappa</p>
                      </div>
                </div>
            </div>
            <!-- Info -->
            <div class="col">
                <img class="logo" src="../assets/img/logo-2.png" alt="">
                <span class="sofbox">SOFBOX</span>

                <h4 class="mt-5">9840 Shore St. Found Du Lac, WI 54935</h4>
                <p class="mt-4 mb-2">0 1223 456 789</p>
                <p>mail@sofbox.com</p>

                <!-- Icons -->
                <div class="buttons">
                    <button class="btn">
                        <i class="fa-brands fa-facebook-f" style="color: #3d84ff;"></i>
                    </button>

                    <button class="btn ms-2">
                        <i class="fa-brands fa-twitter" style="color: #3d84ff;"></i>
                    </button>

                    <button class="btn ms-2">
                        <i class="fa-brands fa-github" style="color: #3d84ff;"></i>
                    </button>

                    <button class="btn ms-2">
                        <i class="fa-brands fa-instagram" style="color: #3d84ff;"></i>
                    </button>
                </div>

                <!-- Get in Touch -->
                <div class="touch mt-5">
                    <h4 class="mb-4">Get in Touch</h4>

                    <div class="mb-4 d-flex">
                        <input type="text" class="form-control" id="name" placeholder="Your Name">

                        <input type="text" class="form-control ms-4" id="email" placeholder="Your Email">

                    </div>

                    <!-- Subject form -->
                    <div class="mb-4">
                        <input type="text" class="form-control" id="subject" placeholder="Your Subject">
                    </div>
                    <!-- Text area -->
                    <div class="mb-4">
                        <textarea class="form-control" id="text-area" rows="8" placeholder="Your Message"></textarea>
                    </div>

                    <button type="button" class="btn btn-primary mt-2 p-3">Send Message</button>
                </div>
            </div>
        </div>
    </div>
    <hr class="mt-5">
</template>

<style scoped lang="scss">
.container {
    margin-top: 150px;
}

p {
    color: hsl(204.71deg 8.13% 59.02%);
}

.title {
    margin-bottom: 80px;
}

.map {
    width: 100%;
}

.logo {
    width: 40px;
}

.sofbox {
    margin-left: 10px;
    color: hsl(219.2deg 100% 60.98%);
    font-size: 20px;
}


.buttons {
    margin-top: 70px;


    .btn {
        height: 50px;
        width: 50px;
        border: 1px solid hsl(204.71deg 8.13% 59.02%);
    }
}



.card {
    width: 60%;
    position: absolute;
    top: 10px;
    left: 30px;
}

a {
    text-decoration: none;
}

.plus-minus-btn {
    position: absolute;
    right: 30px;
    bottom: 335px;

    .btn-plus {
        background-color: white;
        border: none;
        padding: 10px;
        width: 60px;
        height: 60px;
        font-size: 30px;
        color: hsl(0deg 0% 40%);
    }

    .btn-minus {
        background-color: white;
        border: none;
        padding: 10px;
        width: 60px;
        height: 60px;
        font-size: 30px;
        color: hsl(0deg 0% 40%);
    }
}

.ping {
    width: 28px;
    position: absolute;
    top: 215px;
    left: 310px;
}

.mountain {
    width: 50px;
    position: absolute;
    bottom: 340px;
    left: 20px;
    border: 2px solid white;
}

.badges {
    position: absolute;
    left: 90px;
    bottom: 330px;

    .badge {
        background-color: hsl(120deg 28.21% 92.35%);
        height: 20px;
    }
}
</style>