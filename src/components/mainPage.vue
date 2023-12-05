<script>
export default {
    data(){
        return  {

        }
    },
} 
</script>

<template>
    <main>
        <!-- Banner -->
        <section class="banner p-4">
            <div class="container me-5 mt-3">
                <div class="row">
                    <!-- Banner info -->
                    <div class="col-5 m-2">
                        <h1>The biggest platform </h1>
                        <h1 class="mt-3">for your growth</h1>
                        <p class="mt-4">There are many variations of passages of Lorem Ipsum available,but the majority have
                            suffered alteration in some form</p>

                        <button type="button" class="btn btn-primary mt-4 p-3">Read More</button>
                    </div>
                    <!-- Button -->
                    <div class="col-1">
                        <img class="bg-image" src="../assets/img/27-1.png" alt="">
                    </div>
                </div>
            </div>
        </section>
    </main>
</template>

<style scoped lang="scss">
.banner {
    margin: 0 auto;
    width: 80%;
    height: 500px;
    background-color: hsl(216.92deg 100% 97.45%);
}

h1 {
    letter-spacing: 1px;
}

p{
  color: hsl(204.71deg 8.13% 59.02%);
}

button {
    &:hover {
        background-color: black;
    }
}

.col-1 {
    position: relative;
    top: 50px;
}
</style>