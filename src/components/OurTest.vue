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
                <div class="col"></div>
                <div class="col"></div>
            </div>
        </div>
    </section>

    <section>
    </section>
</template>

<style scoped lang="scss">
section {
    .bg-wave {
        filter: opacity(0.2) drop-shadow(0 0 0 hsl(222, 84%, 88%));
        transform: rotate(180deg);
        background-image: url('../assets/img/15.png');
        background-repeat: repeat;
        background-size: cover;
        width: 100%;
        height: 250px;
        position: absolute;
        right: 200px;

        .square {
            height: 200px;
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
}

p {
    color: hsl(204.71deg 8.13% 59.02%);
}
</style>