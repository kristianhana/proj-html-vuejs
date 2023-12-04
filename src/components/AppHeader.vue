<script>
</script>

<template>
    <!-- Navbar -->
    <nav class="navbar">
        <div class="container p-2">
            <!-- Logo -->
            <img class="logo" src="../assets/img/logo-2.png" alt="">

            <!-- Navigation items -->
            <section>
                <div class="d-flex">
                    <!-- Navbar menu -->
                    <ul class="navbar-nav">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#">Home</a>
                        </li>
                    </ul>

                    <!-- Icons -->
                    <span class="icons mt-2 ms-4 ">
                        <i class="fa-solid fa-magnifying-glass" style="color: #000000;"></i>
                        <i class="fa-solid fa-cart-shopping ms-3" style="color: #000000;"></i>
                    </span>

                    <!-- Button -->
                    <button type="button" class="btn btn-primary ms-5">Get Started</button>
                </div>
            </section>
        </div>
    </nav>
</template>

<style scoped lang="scss">
.navbar {
    .container {
        .logo {
            width: 40px;
        }
    }
}
</style>