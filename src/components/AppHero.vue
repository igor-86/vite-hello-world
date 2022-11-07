<script>

export default {
    data() {
        return {
            imageName: "sierra.jpg"
        }
    },
    methods: {
        getImage() {
            return new URL(`../assets/img/${this.imageName}`, import.meta.url).href;
        }
    }
}

</script>

<template>
    <div class="jumbo">
        <img :src="getImage()" alt="">
    </div>
</template>

<style scoped>
.jumbo {
    width: 100%;
    height: 300px;
}

.jumbo>img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
</style>