<script>
    import AppHeader from './components/AppHeader.vue';
    import AppTitle from './components/AppTitle.vue';

export default {
    name: 'App',
    components: {
        AppHeader,
        AppTitle,
    }
}
</script>

<template>
<AppHeader></AppHeader>
<AppTitle></AppTitle>
</template>