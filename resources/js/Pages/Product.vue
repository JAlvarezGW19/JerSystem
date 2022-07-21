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

    <div class="container contenido-producto">

        <div class="nombreCodigoProducto">
            <h6>LG</h6>
            <h2 class="text-muted">Monitor LED 20MK400H 19.5"</h2>
            <p class="text-muted">Código: 15464544</p>
        </div>    

        <div class="carruselProducto">
                <div id="carruselProducto" class="carousel slide" data-bs-ride="carousel">
                    <div class="carousel-inner">
                        <div class="carousel-item active seccion-carousel-producto" data-bs-interval="10000">
                            <img src="../../img/p1.jpg">
                        </div>
                        <div class="carousel-item seccion-carousel-producto" data-bs-interval="2000">
                            <img src="../../img/p2.jpg">
                        </div>
                        <div class="carousel-item seccion-carousel-producto" data-bs-interval="2000">
                            <img src="../../img/p3.jpg">
                        </div>
                        <div class="carousel-item seccion-carousel-producto" data-bs-interval="2000">
                            <img src="../../img/p4.jpg">
                        </div>
                    </div>

                    <button class="carousel-control-prev" type="button" data-bs-target="#carruselProducto" data-bs-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Previous</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#carruselProducto" data-bs-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Next</span>
                    </button>

                    <div class="indicadores-carrusel">
                        <button class=".carousel-indicators active"  data-bs-target="#carruselProducto" data-bs-slide-to="0">
                            <img src="../../img/p1.jpg" width="100%">
                        </button>
                        <button class=".carousel-indicators"  data-bs-target="#carruselProducto" data-bs-slide-to="1">
                            <img src="../../img/p2.jpg" width="100%">
                        </button>
                        <button class=".carousel-indicators active"  data-bs-target="#carruselProducto" data-bs-slide-to="2">
                            <img src="../../img/p3.jpg" width="100%">
                        </button>
                        <button class=".carousel-indicators"  data-bs-target="#carruselProducto" data-bs-slide-to="3">
                            <img src="../../img/p4.jpg" width="100%">
                        </button>
                    </div>
                    
                </div>

        </div>
        
            <br/>
            <br/>

        <div class="precioContactoProducto">

            <p class="texto-especs">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut volutpat molestie nunc. Donec lacinia tempor urna nec ultrices. Integer tortor felis, tempor et arcu sit amet, aliquam lacinia justo. Pellentesque vitae ullamcorper neque. Sed scelerisque ligula eget augue aliquet, id tincidunt leo lobortis.
            </p>

            <h1>S/ 420</h1>
            <p class="text-muted">Stock:>10</p>

                <br/>

            <a href="https://api.whatsapp.com/send?phone=923816243&text=Hola,%20buen%20d%C3%ADa,%20me%20interesa%20el%20producto%20%22X%22,%20quisiera%20m%C3%A1s%20informaci%C3%B3n">
                <button class="btn btn-success boton-contactar">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-whatsapp" width="32" height="32" viewBox="0 0 24 24" stroke-width="1.5" stroke="white" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                        <path d="M3 21l1.65 -3.8a9 9 0 1 1 3.4 2.9l-5.05 .9" />
                        <path d="M9 10a0.5 .5 0 0 0 1 0v-1a0.5 .5 0 0 0 -1 0v1a5 5 0 0 0 5 5h1a0.5 .5 0 0 0 0 -1h-1a0.5 .5 0 0 0 0 1" />
                    </svg>
                    Contactar
                </button>
            </a>
        </div>

        <br/>
        <br/>
        
    </div>

    <div class="container contenido-producto descripcion">
        <div class="container titulo-especs">
            <h6>CARACTERÍSTICAS</h6>
        </div>
        <P class="texto-especs">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut volutpat molestie nunc. Donec lacinia tempor urna nec ultrices. Integer tortor felis, tempor et arcu sit amet, aliquam lacinia justo. Pellentesque vitae ullamcorper neque. Sed scelerisque ligula eget augue aliquet, id tincidunt leo lobortis. Nunc auctor libero mauris, vitae ultrices risus sodales in. Integer id hendrerit dolor. Nullam a erat sit amet magna tempus eleifend eget eget odio. Mauris tristique euismod consectetur. Maecenas ut mattis dui. In hac habitasse platea dictumst.

Cras pretium leo ut orci lobortis, in blandit tortor scelerisque. In eu diam a nunc porta hendrerit. Etiam varius justo a massa fermentum, eu placerat nibh tristique. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Donec scelerisque, massa nec hendrerit gravida, ante lacus finibus lacus, commodo condimentum tellus sapien et turpis. Etiam enim tellus, consequat facilisis commodo ut, vulputate eget metus. Aliquam congue ullamcorper enim, id congue arcu volutpat vel. Mauris id lobortis dui. Aenean quam leo, condimentum non neque a, rhoncus rhoncus sapien. Sed et mauris elementum, condimentum tortor et, eleifend ligula. Sed consectetur dictum lectus quis vulputate. Mauris imperdiet, sem et cursus varius, sapien sem placerat lectus, ac congue purus dolor nec velit. Nam sed gravida massa, quis finibus sapien.

Nulla congue aliquet purus nec commodo. Phasellus dignissim mattis neque, id tempus urna fringilla ac. Vivamus scelerisque condimentum ipsum nec ornare. Suspendisse faucibus est a nisi mattis, eget pellentesque justo pharetra. Aenean non nisl vitae erat pellentesque pulvinar. Quisque quis dui dolor. Sed volutpat ante non hendrerit condimentum. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean at venenatis nisi. Donec finibus eros ut metus facilisis gravida. Etiam consequat sed tellus non egestas. Morbi nisi dui, laoreet sed feugiat et, egestas eget arcu.    
        </P>
    </div>

    <div class="container contenido-producto descripcion">
        <div class="container titulo-especs">
            <h6>ESPECIFICACIONES TÉCNICAS</h6>
        </div>
        <P class="texto-especs">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum vehicula ante ac justo mattis tincidunt. Cras at lacus bibendum, porta risus quis, mollis felis. Fusce risus tortor, dictum vel neque nec, facilisis maximus enim. Nulla lorem elit, malesuada ac turpis ut, scelerisque luctus nibh. Duis suscipit enim et lacinia convallis. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed nec metus porttitor ex tristique faucibus. Nullam massa purus, gravida vitae eleifend at, tincidunt vitae felis.</P>
    </div>

    <TheFooter />

</template>

<style>

    .contenido-producto{
        margin-top: 2rem;
        background-color: white;
        padding: 1rem;
    }
        @media (min-width:768px){
            .contenido-producto{
                display: grid;
                grid-template-columns: repeat(2,1fr);
            }
            .carruselProducto{
                grid-column: 1 / 2;
                grid-row: 1/2;
            }
            .nombreCodigoProducto{
                grid-column: 2 / 3;
                grid-row: 1/2;
                padding: 2rem;
            }
            .precioContactoProducto{
                grid-column: 2 / 3;
                grid-row: 1/2;
                padding: 11rem 2rem 0rem 2rem; 
            }
            .seccion-carousel-producto img{
                height: 30rem;
                width: 30rem;
            }
        }
    .seccion-carousel-producto img{
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center;
        height: 24rem;
        width: 100%;
        margin-bottom: 2rem;
    }
        @media(min-width: 480px){
            .seccion-carousel-producto img{
                height: 30rem;
            }
        }
        @media(min-width: 500px){
            .seccion-carousel-producto img{
                height: 33rem;
            }
        }
    .indicadores-carrusel{     
        display: grid;
        grid-template-columns: repeat(4,1fr);
        height: 5rem;
    }

        @media (min-width: 768px){
            .indicadores-carrusel{
                display: grid;
                grid-template-columns: repeat(4,1fr);
                width: 75%;
                height: 2rem;
                padding-left: 8rem;
            }
        }
    .carousel-control-prev, .carousel-control-next{
        height: 71%;
    }
    .boton-contactar{
        width: 100%;
    }
    .titulo-especs{
        background-color: lightgray;
        height: 3rem;
        padding: 1rem;
        text-align: center;
    }
    .texto-especs{
        padding: 1rem;
        text-align: justify;
    }
        @media (min-width: 768px){
            .descripcion{
                display: block;
            }
        }
        @media (max-width: 767px){
            .precioContactoProducto{
                padding: 1rem;
            }
        }
</style>