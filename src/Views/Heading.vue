<template>
    <header>
        <h1 id="board-title">{{ boardLetters }} - {{ boardTitle }}</h1>
    </header>
</template>

<script>
    export default {
        name: "heading",
        data() {
            return {
                boardLetters: "/>p/",
                boardTitle: "Implying we can programming"
            }
        }
    }
</script>

<style scoped>
    #board-title {
        text-align: center;
    }
</style>