<script setup>
</script>

<template>
    <nav class="navbar navbar-expand-lg navbar-light navbar-principal">
        <div class="container">
            <a class="navbar-brand titulo" href="/">JerSystem</a>

            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarScroll"
                aria-controls="navbarScroll" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarScroll">
                <form class="d-flex">
                    <div class="buscador input-group">
                        
                        <input class="form-control buscador-tamaño" type="search" placeholder="Buscar" aria-label="Search">
                        <button class="btn btn-light input-group-text" type="submit">
                            <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-search" width="24" height="24" viewBox="0 0 24 24" stroke-width="1.5" stroke="#2c3e50" fill="none" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                            <circle cx="10" cy="10" r="7" />
                            <line x1="21" y1="21" x2="15" y2="15" />
                            </svg>
                        </button>
                    </div>
                </form>
            </div>
        </div>
    </nav>
    <nav class="navbar navbar-expand-lg navbar-light navbar-secundario">
        <div class="container">
            <ul class="navbar-nav me-auto my-2 my-lg-0 navbar-nav-scroll" style="--bs-scroll-height: 100px;">

                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarScrollingDropdown" role="button"
                            data-bs-toggle="dropdown" aria-expanded="false">
                            <span class="texto-categorias">Categorías</span>
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="navbarScrollingDropdown">
                            <li><a class="dropdown-item" href="#">Computadoras</a></li>
                            <li><a class="dropdown-item" href="#">Laptops</a></li>
                            <li><a class="dropdown-item" href="#">Impresoras</a></li>
                        </ul>
                    </li>

                </ul>
        </div>
    </nav>

</template>

<style>
    body{
        background-color: rgb(245, 241, 241);
    }
    .navbar-principal{
        background-color: #21618C;
        padding: 0.8rem;
    }
    .navbar-secundario{
        background-color: #2874A6;
        padding-top: 0.15rem;
        padding-bottom: 0.15rem;
    }
    .titulo{
        margin-right: 4rem;
    }
    .texto-categorias{
        margin-left: 1rem;
        color: white;
    }
    .dropdown ul {
    background-color: #2874A6 !important;
    }
    .dropdown li a {
    color: white !important;
    }
    .dropdown li a:hover {
    color: black !important;
    }
    .navbar li a, .navbar .navbar-brand {
        color: #fff !important;
    }

    .buscador {
        margin-top: 1rem;
    }
        
        @media (min-width:991px){
            .buscador {
                margin: 0;
            }
        }

        @media (min-width:768px){
            .buscador-tamaño{
                padding-right: 34rem;
            }
        }
        
</style>