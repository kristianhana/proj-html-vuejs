<script>
export default {
}
</script>

<template>
    <div class="container p-5">
        <div class="row row-cols-3">
            <div class="col d-flex">
                <!-- Logo -->
                <div class="d-flex me-3">
                    <img class="marketing-logo" src="../assets/img/24.png" alt="">

                </div>
                <!-- Info and List -->
                <div>
                    <h4 class="mb-3">Online Marketing</h4>
                    <p class="mb-4">It is a long established fact that a reader will be distracted.</p>

                    <ul>
                        <li>SEO</li>
                        <li>SEM</li>
                        <li>Website Strategy</li>
                        <li>Social managiament</li>
                    </ul>
                </div>
            </div>

            <div class="col d-flex">
                <!-- Logo -->
                <div class="d-flex me-3">
                    <img class="marketing-logo" src="../assets/img/24.png" alt="">

                </div>
                <!-- Info and List -->
                <div>
                    <h4 class="mb-3">Online Marketing</h4>
                    <p class="mb-4">It is a long established fact that a reader will be distracted.</p>

                    <ul>
                        <li>SEO</li>
                        <li>SEM</li>
                        <li>Website Strategy</li>
                        <li>Social managiament</li>
                    </ul>
                </div>
            </div>

            <div class="col d-flex">
                <!-- Logo -->
                <div class="d-flex me-3">
                    <img class="marketing-logo" src="../assets/img/24.png" alt="">

                </div>
                <!-- Info and List -->
                <div>
                    <h4 class="mb-3">Online Marketing</h4>
                    <p class="mb-4">It is a long established fact that a reader will be distracted.</p>

                    <ul>
                        <li>SEO</li>
                        <li>SEM</li>
                        <li>Website Strategy</li>
                        <li>Social managiament</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">

.container {
    margin-top: 120px;
}

img {
    align-self: self-start;
    width: 60px;
}

p {
    color: hsl(204.71deg 8.13% 59.02%);
}

ul {
    list-style: none;
    padding: 1rem;
    li {
        &:before {
            content: '✔';
            color: hsl(219deg 100% 60.78%);
            font-size: 20px;
            margin-right: 20px;
        }
    }
}
</style>