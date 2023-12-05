<script>
export default {
    data(){
        return {  
        }  
    },

    props: {
        menu: String,
    },
}
</script>

<template>
    <ul class="navbar-nav me-3 mt-2">
        <li class="nav-item">
            <a :class="menu == 'Home'  ? 'nav-link active' : 'nav-link'" aria-current="page" href="#">
                {{ menu }}
            </a>
        </li>
    </ul>
</template>

<style scoped lang="scss">
.navbar {
    .nav-item {
        min-height: 50px;
        .active {
            border-bottom: 3px solid rgb(0, 128, 255);
            color: rgb(0, 128, 255);
        }
        .nav-link {
            &:hover {
                color: rgb(0, 128, 255);
                border-bottom: 3px solid rgb(0, 128, 255);
            }
        }
    }
}
</style>