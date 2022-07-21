<script setup>

import { Link } from '@inertiajs/inertia-vue3';

defineProps({
    product: Object,
})
</script>

<template>
    <!--<div class="card" style="width: 18rem;">
        <img src="../../../img/C2.jpg" class="card-img-top" alt="...">
        <div class="card-body">
            <h5 class="card-title">{{ product.name }}</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
                content.</p>
            <button class="btn btn-primary" @click="$inertia.get(`/products/${product.id}`)">Go somewhere</button>
        </div>
    </div>-->
    <div class="card" style="width: 13rem;">
        <a href="/product"><img src="@/../img/p1.jpg" class="card-img-top" alt="..."></a>
        <a class="texto-card-body" href="/product">
            <div class="card-body" role="button" link="/product">
                <h6 class="card-title">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</h6>
                    <p class="card-text">
                        <span class="text-muted">S/ 420</span>
                    </p>
            </div>
        </a>
    </div>
</template>

<style>
.card-text{
    text-align: right;
}
.card {
    margin-bottom: 2rem;
    background-color: var(--fondo);
}
.texto-card-body{
    text-decoration: none;
    color: black;
}
.texto-card-body:hover{
    color: black;
}
</style>