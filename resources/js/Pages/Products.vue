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

        <div>

            <div class="row">
        
                <TheFilter/>

                <div class="col col-md-7 order-2 mx-3 contenedor-productos">

                        <!--<div class="contenedor-cards" v-for="product in products" :key="product.id">
                            <TheCard :product="product" />
                        </div>-->

                        <div class="contenedor-cards">
                            <TheCard/>
                        </div>

                        <div class="contenedor-cards">
                            <TheCard/>
                        </div>

                        <div class="contenedor-cards">
                            <TheCard/>
                        </div>

                        <div class="contenedor-cards">
                            <TheCard/>
                        </div>

                        <div class="contenedor-cards">
                            <TheCard/>
                        </div>

                        <div class="contenedor-cards">
                            <TheCard/>
                        </div>

                        <div class="contenedor-cards">
                            <TheCard/>
                        </div>

                        <div class="contenedor-cards">
                            <TheCard/>
                        </div>

                </div>

            </div>

        </div>

    <TheFooter />

</template>

<style>
.resultados {
    margin: 2rem 0 3rem 0;
    text-align: center;
}
.contenedor-productos{
    padding: 0 2rem 2rem 2rem;
    margin-right: 1rem;
    display: grid;
    gap: 1.5rem;
}
    @media (max-width: 767px){
        .contenedor-productos{
            justify-content: center;
            margin-top: 2rem;         
        }
        .contenedor-cards{
            margin: 0 auto;
        }
    }
    @media (min-width: 500px){
        .contenedor-productos{
            grid-template-columns: repeat(2,1fr);
        }
    }
    @media (min-width: 980px){
        .contenedor-productos{
            grid-template-columns: repeat(3,1fr);
        }
    }
    @media (min-width: 1290px){
        .contenedor-productos{
            grid-template-columns: repeat(4,1fr);
        }
    }

</style>