<script>
export default {
    data() {
        return {
            jumImg: "https://unsplash.it/1920/1080?image"
        }
    }
}
</script>
<template>
    <img :src="jumImg" alt="Jumbotron">
</template>

<style>
img {
    position: relative;
    width: 100%;
}
</style>