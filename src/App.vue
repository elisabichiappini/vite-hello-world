<script>
import HeroComponent from './components/HeroComponent.vue';
export default {
    name: 'AppTitle',
    data() {
        return {
            title: 'La mia prima App con Vite',
        };
    },
    compontents: {
        HeroComponent,
    },
    components: { HeroComponent }
}
</script>

<template>
  <HeroComponent/>
  <h1>{{ title }}</h1>
</template>

<style scoped></style>
