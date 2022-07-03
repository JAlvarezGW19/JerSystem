<script setup>
import { Head, Link } from '@inertiajs/inertia-vue3';
import TheNavbar from '@/Components/home/TheNavbar.vue';
import TheCard from '@/Components/home/TheCard.vue';

defineProps({
    canLogin: Boolean,
    canRegister: Boolean,
    laravelVersion: String,
    phpVersion: String,
})
</script>

<template>

    <Head title="Welcome" />
    <TheNavbar />

    <TheCard title="Impresora" />
</template>

