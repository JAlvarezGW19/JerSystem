<script setup>
</script>

<template>
    <div id="carruselPrincipal" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active seccion-carousel imagen-carousel-1" data-bs-interval="10000">
            </div>
            <div class="carousel-item seccion-carousel imagen-carousel-2" data-bs-interval="2000">
            </div>
            <div class="carousel-item seccion-carousel imagen-carousel-3" data-bs-interval="2000">
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carruselPrincipal" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carruselPrincipal" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>
</template>