<script setup>
</script>

<template>
    <footer class="pb-2 pt-5 mt-5 color-footer">
        <div class="container">
            <div class="row">
            <div class="col-6 col-md-3 mb-5">
                <div class="imagen-footer">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-headset" width="100" height="100" viewBox="0 0 24 24" stroke-width="1" stroke="#2c3e50" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                        <rect x="4" y="13" rx="2" width="4" height="6" />
                        <rect x="16" y="13" rx="2" width="4" height="6" />
                        <path d="M4 15v-3a8 8 0 0 1 16 0v3" />
                        <path d="M18 19a6 3 0 0 1 -6 3" />
                    </svg>
                </div>
                <h5>Comuníquese con nosotros</h5>
                <ul class="nav flex-column">
                <li class="nav-item mb-2 text-muted">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-phone" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#2c3e50" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                        <path d="M5 4h4l2 5l-2.5 1.5a11 11 0 0 0 5 5l1.5 -2.5l5 2v4a2 2 0 0 1 -2 2a16 16 0 0 1 -15 -15a2 2 0 0 1 2 -2" />
                    </svg>
                    923 816 243
                </li>
                <li class="nav-item mb-2 text-muted">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-mail" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#2c3e50" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                        <rect x="3" y="5" width="18" height="14" rx="2" />
                        <polyline points="3 7 12 13 21 7" />
                    </svg>
                    juan271@hotmail.com
                </li>
                </ul>
            </div>

            <div class="col-6 col-md-3 mb-5">
                <div class="imagen-footer">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-location" width="100" height="100" viewBox="0 0 24 24" stroke-width="1" stroke="#2c3e50" fill="none" stroke-linecap="round" stroke-linejoin="round">
                    <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                    <path d="M21 3l-6.5 18a0.55 .55 0 0 1 -1 0l-3.5 -7l-7 -3.5a0.55 .55 0 0 1 0 -1l18 -6.5" />
                    </svg>
                </div>
                <h5>Ubícanos</h5>
                <ul class="nav flex-column">
                    <li class="nav-item mb-2 text-muted">
                        <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-map-pin" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#2c3e50" fill="none" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                            <circle cx="12" cy="11" r="3" />
                            <path d="M17.657 16.657l-4.243 4.243a2 2 0 0 1 -2.827 0l-4.244 -4.243a8 8 0 1 1 11.314 0z" />
                        </svg>
                        Jr. Espinar #400, Chimbote, Perú
                    </li>
                </ul>
            </div>

            </div>

            <div class="d-flex flex-column flex-sm-row justify-content-between py-4 border-top">
            <p>&copy; JerSystem. Todos los derechos reservados.</p>
            <ul class="list-unstyled d-flex">
                <li class="ms-3"><a class="link-dark" href="#"><svg class="bi" width="24" height="24"><use xlink:href="#twitter"/></svg></a></li>
                <li class="ms-3"><a class="link-dark" href="#"><svg class="bi" width="24" height="24"><use xlink:href="#instagram"/></svg></a></li>
                <li class="ms-3"><a class="link-dark" href="#"><svg class="bi" width="24" height="24"><use xlink:href="#facebook"/></svg></a></li>
            </ul>
            </div>
        </div>
    </footer>
</template>

<style>
    .color-footer{
        background-color: white;
    }
    .imagen-footer{
        display: flex;
        justify-content: center;
    }
</style>