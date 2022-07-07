<script setup>
import { Head, Link } from '@inertiajs/inertia-vue3';
import TheNavbar from '@/Components/home/TheNavbar.vue';
import TheFooter from '@/Components/home/TheFooter.vue';

defineProps({
    canLogin: Boolean,
    canRegister: Boolean,
    laravelVersion: String,
    phpVersion: String,
    product: Object,
})
</script>

<template>

    <Head title="JerSystem" />
    <TheNavbar />

    <p>{{ product.name }}</p>

    <TheFooter />

</template>