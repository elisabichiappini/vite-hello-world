<script>
export default {
    name: 'titleComponent',
    data() {
        return {
            title: 'Ciao sono keyup :)',
        }
    }
}
</script>

<template>
    <header>
        <h1>{{ title }}</h1>
    </header>
</template>
