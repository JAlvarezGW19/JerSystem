<script setup>
import TheFilterMenu from "./TheFilterMenu.vue";
</script>

<template>
<!-- Comienzo del menú de busqueda filtrada -->

        


        <div class="col-md-4 col-lg-3 order-md-1 mb-3">

          <nav class="navbar navbar-dark navbar-filtro">
          <div class="container-fluid">
            <h4 class="texto-filtro">Filtro de busqueda</h4>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarToggleExternalContent" aria-controls="navbarScroll" aria-expanded="false" aria-label="Toggle navigation">
              <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-filter" width="30" height="30" viewBox="0 0 24 24" stroke-width="0.5" stroke="white" fill="none" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                            <path d="M5.5 5h13a1 1 0 0 1 .5 1.5l-5 5.5l0 7l-4 -3l0 -4l-5 -5.5a1 1 0 0 1 .5 -1.5" />
                          </svg>
            </button>
          </div>
        </nav>
        <div class="collapse" id="navbarToggleExternalContent">
          <div class="bg-gray p-4 filtro-sm">
            <TheFilterMenu />
          </div>
        </div>
        <div class="filtro-lg">
          <TheFilterMenu />
        </div>
            
          
        </div>


    <!-- Fin del menú de busqueda filtrada -->
</template>

<style>
.navbar-filtro{
  background-color: #4f575e;
}
  @media (min-width: 767px){
        .navbar-filtro{
            display: none;
        }
        .filtro-sm ul .list-group{
          display: none;
        }
        .filtro-sm ul .titulo-filtro{
          display: none;
        }
  }
  @media (max-width: 767px){
         .filtro-lg .list-group{
          display: none;
        }
         .filtro-lg .titulo-filtro{
          display: none;
        }
  }
.list-group-item{
  background-color: var(--fondo);
  border: 0;
  margin: 0 1rem;
}
.texto-filtro{
  color: white;
}
</style>