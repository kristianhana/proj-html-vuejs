<script>
import FooterMenu from './FooterMenu.vue';

export default {
    data() {
        return {
            navTitle: ["Menu", "About us", "Quick Links",],
            menuLinks:
                ["About us",
                    "Theme",
                    "Features",
                    "Pricing",
                    "Blog",
                ],
        }
    },

    components: { FooterMenu },
}
</script>

<template>
    <div class="container">
        <div class="row row-cols-4">
            <div class="col info">
                <img class="logo" src="../assets/img/logo-2.png" alt="">
                <span class="sofbox">SOFBOX</span>
                <p class="mt-3">It is a long established fact that a reader will
                    be distracted by the readable content.
                </p>

                <div class="d-flex">
                    <p>
                        Copyrigth @ 2018
                    <p class="text-primary ms-2">Sofbox</p>
                    </p>
                </div>
            </div>

            <div class="col" v-for="title in navTitle">
                <FooterMenu :title="title" />
                <div v-for="links in menuLinks">
                    <FooterMenu :links="links" />
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.container {
    margin-top: 70px;
}

.logo {
    width: 40px;
}

.sofbox {
    margin-left: 10px;
    color: hsl(219.2deg 100% 60.98%);
    font-size: 20px;
}

p {
    color: hsl(204.71deg 8.13% 59.02%);
}


.col {
    width: 25%;
}
</style>