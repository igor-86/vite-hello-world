<script>

export default {
    data() {
        return {
            firstMessage: "La mia prima App Vite!"
        }
    }
}

</script>

<template>
    <h1>{{ firstMessage }}</h1>
</template>

<style scoped>
h1 {
    color: red;
    text-align: center;
}
</style>