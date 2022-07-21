<script setup>
import { Head, Link } from '@inertiajs/inertia-vue3';
import TheFooter from '@/Components/home/TheFooter.vue';
import TheNavBarNosotros from '@/Components/home/TheNavBarNosotros.vue';

defineProps({
    canLogin: Boolean,
    canRegister: Boolean,
    laravelVersion: String,
    phpVersion: String,
})
</script>

<template>

    <Head title="JerSystem" />
    <TheNavBarNosotros />

    <h2 class="titulo-nosotros text-muted">Nosotros</h2>

    <main>

        <div class="contenedor-nosotros sombra col-9">

            

            <h3 class="titulo-nosotros__contenido">Misión</h3>
                <p>Donec sed dolor auctor, pretium tellus et, suscipit libero. Aliquam pharetra tellus aliquet, suscipit dui a, sollicitudin ante. Sed sed porttitor urna, et congue elit. Pellentesque non blandit enim. Aenean tristique sem ac efficitur luctus. Quisque fringilla id diam tristique sodales. Suspendisse eget turpis vitae urna vehicula imperdiet a quis mi. Aenean iaculis faucibus erat, vitae vestibulum odio laoreet vitae. In eu pellentesque est, ut maximus est. Fusce ac metus tincidunt, ultricies sem non, vulputate neque. Nullam quis pretium urna, in ultricies justo. Sed ut eros at arcu venenatis fermentum vel nec augue. Ut blandit elit vestibulum ante porta, a viverra lorem dictum. Donec vestibulum eros vel quam tempus malesuada. Donec justo lacus, ultricies sit amet mauris eu, feugiat interdum mi. Vestibulum enim nibh, egestas ut efficitur a, suscipit vel nulla. Nunc tincidunt mollis magna, in hendrerit orci faucibus in. Nulla dictum pulvinar pretium. Fusce feugiat risus et egestas gravida. Nulla enim lacus, iaculis sed lacus in, gravida euismod metus. Vestibulum eget risus dapibus, dignissim ipsum et, gravida eros.</p>
                <p>Aenean iaculis faucibus erat, vitae vestibulum odio laoreet vitae. In eu pellentesque est, ut maximus est. Fusce ac metus tincidunt, ultricies sem non, vulputate neque. Nullam quis pretium urna, in ultricies justo. Sed ut eros at arcu venenatis fermentum vel nec augue. Ut blandit elit vestibulum ante porta, a viverra lorem dictum. Donec vestibulum eros vel quam tempus malesuada. Donec justo lacus, ultricies sit amet mauris eu, feugiat interdum mi. Vestibulum enim nibh, egestas ut efficitur a, suscipit vel nulla. Nunc tincidunt mollis magna, in hendrerit orci faucibus in. Nulla dictum pulvinar pretium. Fusce feugiat risus et egestas gravida. Nulla enim lacus, iaculis sed lacus in, gravida euismod metus. Vestibulum eget risus dapibus, dignissim ipsum et, gravida eros.</p>

        </div>
    </main>

    <TheFooter />

</template>