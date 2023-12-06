<script>
export default {
    data() {
        return {
        }
    },
    props: {
        title: String,
        links: String
    },
}
</script>

<template>
    <div class="col">
        <h5>{{ title }}</h5>
        <p>{{ links }}</p>
    </div>
</template>

<style scoped lang="scss">
p {
    color: hsl(204.71deg 8.13% 59.02%);
}
</style>