<script setup>
import { Head, Link } from '@inertiajs/inertia-vue3';
import TheNavbar from '@/Components/home/TheNavbar.vue';
import TheCarousel from '@/Components/home/TheCarousel.vue';
import TheFooter from '@/Components/home/TheFooter.vue';
import TheMenuCategories from '../Components/home/TheMenuCategories.vue';

defineProps({
    canLogin: Boolean,
    canRegister: Boolean,
    laravelVersion: String,
    phpVersion: String,
})
</script>

<template>

    <Head title="JerSystem" />
    <TheNavbar />

    <TheCarousel />

    <TheMenuCategories />

    <TheFooter />

</template>
