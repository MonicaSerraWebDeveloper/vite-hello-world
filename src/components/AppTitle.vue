<script>
    export default {
        name: 'AppTitle',
        data() {
            return {
                firstTitleInVite: 'La mia prima app con Vite!'
            }
        }
    }
</script>

<template>
    <h1>{{ firstTitleInVite }}</h1>
</template>

<style>

    h1 {
        font-family: Arial, Helvetica, sans-serif;
        text-align: center;
    }

</style>