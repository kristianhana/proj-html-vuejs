<script>
export default {
    props: {
        menu: String,
    },
}
</script>

<template>
    <ul class="navbar-nav me-3 mt-2">
        <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">
                {{ menu }}
            </a>
        </li>
    </ul>
</template>

<style scoped lang="scss">
.navbar {
    .nav-item {
        .nav-link {
            &:hover {
                border-bottom: 3px solid rgb(0, 128, 255);
            }
        }
    }
}
</style>