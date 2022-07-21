<script setup>
</script>

<template>
    <nav class="navbar navbar-expand-lg navbar-light navbar-principal">
        <div class="container">
            
            <a class="navbar-brand titulo" href="/"><img src="@/../img/logo.png"></a>

            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarScroll"
                aria-controls="navbarScroll" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarScroll">
                <form class="d-flex">
                    <div class="buscador input-group">
                        
                        <input class="form-control buscador-tamaño" placeholder="Buscar" aria-label="Search">
                        <button class="btn btn-color input-group-text" type="submit">
                            <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-search" width="24" height="24" viewBox="0 0 24 24" stroke-width="1.5" stroke="#fff" fill="none" stroke-linecap="round" stroke-linejoin="round">
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
    <nav class="navbar navbar-expand navbar-light navbar-secundario">
        <div class="container">
            <ul class="navbar-nav me-auto my-2 my-lg-0 navbar-nav-scroll" style="--bs-scroll-height: 100px;">

                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarScrollingDropdown" role="button"
                            data-bs-toggle="dropdown" aria-expanded="false">
                        <span class="texto-categorias">Categorías</span>
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarScrollingDropdown">
                        <li><a class="dropdown-item" href="/products">Computadoras</a></li>
                        <li><a class="dropdown-item" href="/products">Laptops</a></li>
                        <li><a class="dropdown-item" href="/products">Tablets</a></li>
                        <li><a class="dropdown-item" href="/products">Tarjetas madre</a></li>
                        <li><a class="dropdown-item" href="/products">Procesadores</a></li>
                        <li><a class="dropdown-item" href="/products">Discos duros</a></li>
                        <li><a class="dropdown-item" href="/products">Tarjetas de video</a></li>
                        <li><a class="dropdown-item" href="/products">Multimedia</a></li>
                        <li><a class="dropdown-item" href="/products">Fuentes de poder</a></li>
                        <li><a class="dropdown-item" href="/products">Cases</a></li>
                        <li><a class="dropdown-item" href="/products">Monitores</a></li>
                        <li><a class="dropdown-item" href="/products">Teclados</a></li>
                        <li><a class="dropdown-item" href="/products">Mouses</a></li>
                        <li><a class="dropdown-item" href="/products">Impresoras</a></li>
                        <li><a class="dropdown-item" href="/products">Redes</a></li>
                        <li><a class="dropdown-item" href="/products">Software</a></li>
                        <li><a class="dropdown-item" href="/products">Servidores</a></li>
                        <li><a class="dropdown-item" href="/products">Suministros</a></li>
                        <li><a class="dropdown-item" href="/products">UPS's</a></li>
                        <li><a class="dropdown-item" href="/products">Accesorios</a></li>
                        <li><a class="dropdown-item" href="/products">Otros</a></li>
                    </ul>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="/nosotros" role="button">
                        <span class="texto-categorias">¿Quiénes somos?</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="/vision" role="button">
                        <span class="texto-categorias">Visión</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="mision" role="button">
                        <span class="texto-categorias">Misión</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="historia" role="button">
                        <span class="texto-categorias">Historia</span>
                    </a>
                </li>
            </ul>
        </div>
    </nav>

</template>