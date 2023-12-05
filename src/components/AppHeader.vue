<script>
import HeaderMenu from "./HeaderMenu.vue"

export default {
    data() {
        return {
           navMenu: ["Home","About us", "Feature", "Testimonials", "Contact US"],
        }
    },

    components: {HeaderMenu},
}
</script>

<template>
    <!-- Navbar -->
    <nav class="navbar">
        <div class="container p-1">
            <!-- Logo -->
            <img class="logo" src="../assets/img/logo-2.png" alt="">

            <!-- Navigation items -->
            <section>
                <div class="d-flex">
                    <!-- Navbar menu -->
                    <ul v-for="(menu, index) in navMenu">
                        <HeaderMenu :menu="menu" />
                    </ul>

                    <!-- Icons -->
                    <span class="icons mt-2 ms-3 mt-3">
                        <a href="">
                            <i class="fa-solid fa-magnifying-glass" style="color: #000000;"></i>
                        </a>

                        <a href="">
                            <i class="fa-solid fa-cart-shopping ms-4" style="color: #000000;"></i>
                        </a> 
                    </span>

                    <!-- Button -->
                    <button type="button" class="btn btn-primary ms-5 mt-2">Get Started</button>
                </div>
            </section>
        </div>
    </nav>
</template>

<style scoped lang="scss">
.navbar {
    .container {
        width: 80%;
        margin: 0 auto;
        .logo {
            width: 40px;
        }
    }
}

button {
    align-self: flex-start;
}
</style>