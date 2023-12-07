<script>
export default {
    name: 'jumbotronComponent',
    data() {
        return {
            subtitle: 'un pò sciamana, un pò polentona',
        }
    }
}
</script>

<template>
    <header>
        <h2>{{ subtitle }}</h2>
    </header>
</template>


<style scoped>
h2 {
    background-color: pink;
    color: rgb(31, 31, 31);
}
</style>