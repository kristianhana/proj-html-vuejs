<script>
</script>

<template>
    <section>
        <div class="bg-wave">
            <img src="" alt="">
            <div class="square"></div>
        </div>
        <div class="container text-center">
            <h2 class="mb-4">Our Testimonials</h2>
            <p>If you are planning on developing a product landing app or website, take a look at this beautiful-crafted</p>
            <div class="row">
                <div class="col">
                    <!-- Cards -->
                    <section class="container-card p-5">
                        <div class="card-stack">
                            <ul class="card-list">
                                <li class="card"></li>
                                <li class="card"></li>
                                <li class="card">
                                    <img class="person-img" src="../assets/img/27.jpeg" alt="">
                                </li>
                            </ul>
                        </div>
                    </section>
                </div>
                <div class="col">
                    <!-- Cards -->
                    <section class="container-card p-5">
                        <div class="card-stack2">
                            <ul class="card-list">
                                <li class="card"></li>
                                <li class="card"></li>
                                <li class="card">
                                    <img class="person-img" src="../assets/img/26.jpeg" alt="">
                                </li>
                            </ul>
                        </div>
                    </section>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
section {
    .bg-wave {
        filter: opacity(0.2) drop-shadow(0 0 0 hsl(222, 84%, 88%));
        transform: rotate(180deg);
        background-image:url('../assets/img/15.png');
        background-repeat: repeat;
        background-size: cover;
        width: 100%;
        height: 300px;
        position: absolute;
        right: 100px;

        .square {
            height: 240px;
            width: 200px;
            background-color: hsl(222, 84%, 88%);
            position: absolute;
            left: -200px;
            top: 7px;
            filter: opacity(0.3) drop-shadow(0 0 0 hsl(222, 84%, 88%));
        }
    }
}


.container {
    margin-top: 100px;
    width: 30%;
    position: relative; 
}

.container-card {
    position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  margin: 25vh auto 0;
  transform: translateY(-50%);
}

p {
    color: hsl(204.71deg 8.13% 59.02%);
}


.card-stack {
    width: 450px;
    height: 400px;
    position: absolute;
    margin: 60px auto;
    .card-list {
        li {
            border-radius: 2px;
            position: absolute;
            list-style: none;
            height: 300px;
            box-shadow: 0 1px 4px 1px rgba(0, 0, 0, 0.2);
            left: 0;
            right: 0;
            margin: 0 auto;
            text-align: center;
            border: none;

            &:nth-child(1) {
                top: 20px;
                width: 400px;

            }

            &:nth-child(2) {
                top: 10px;
                width: 420px;

            }
        }
    }
}

.card-stack2 {
    width: 450px;
    height: 400px;
    position: absolute;
    margin: 60px auto;
    right: 200px;

    .card-list {
        li {
            border-radius: 2px;
            position: absolute;
            list-style: none;
            height: 300px;
            box-shadow: 0 1px 4px 1px rgba(0, 0, 0, 0.2);
            left: 0;
            right: 0;
            margin: 0 auto;
            text-align: center;
            border: none;
            

            &:nth-child(1) {
                top: 20px;
                width: 400px;

            }

            &:nth-child(2) {
                top: 10px;
                width: 420px;

            }
        }
    }
 
    
}

.person-img {
    position: relative;
    top: 25%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 70px;
    border-radius: 50%;
}
</style>