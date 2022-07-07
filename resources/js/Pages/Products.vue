<script setup>
import { Head, Link } from '@inertiajs/inertia-vue3';
import TheNavbar from '@/Components/home/TheNavbar.vue';
import TheFooter from '@/Components/home/TheFooter.vue';
import TheCard from '@/Components/home/TheCard.vue';
import TheFilter from '../Components/home/TheFilter.vue';

defineProps({
    canLogin: Boolean,
    canRegister: Boolean,
    laravelVersion: String,
    phpVersion: String,
    products: Array,
})
</script>

<template>

    <Head title="JerSystem" />
    <TheNavbar />

    <h3 class="resultados">RESULTADOS</h3>

    <div class="contenedor-principal-lista">

        <TheFilter class="filtro-lista" />

        <div class="contenido-lista">

            <div class="contenedor-cards" v-for="product in products" :key="product.id">
                <TheCard :product="product" />
            </div>

            <!-- <div class="contenedor-cards">
                <TheCard title="Computadora I5, 16Gb RAM, 480Gb SSD " />
            </div>

            <div class="contenedor-cards">
                <TheCard title="Computadora I5, 16Gb RAM, 480Gb SSD " />
            </div>

            <div class="contenedor-cards">
                <TheCard title="Computadora I5, 16Gb RAM, 480Gb SSD " />
            </div> -->

        </div>

    </div>

    <TheFooter />

</template>

<style>
.resultados {
    margin-top: 2rem;
    text-align: center;
}

.contenedor-principal-lista {
    margin-top: 2rem;
    display: grid;
    grid-template-columns: 1fr 3fr;
}

.contenido-lista {
    margin-top: 2rem;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
}

.filtro-lista {
    grid-column: 1 / 2;
    grid-row: 1 / 2;
    width: 100%;
    padding-left: 1rem;
    padding-right: 2rem;
}

.contenedor-cards {
    padding: 1rem;
}
</style>