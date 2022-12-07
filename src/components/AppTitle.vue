<script>

export default {
    data() {
        return {
            title: "La mia prima app con Vite!"
        }
    }
}
</script>

<template>

    <h1>
        {{ title }}
    </h1>

</template>

<style scoped>
h1 {
    color: green;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: black;
    padding: 10px;
    border-radius: 15px;
}
</style>
