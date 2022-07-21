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

            

            <h3 class="titulo-nosotros__contenido">Visión</h3>
                <p>Vivamus pharetra tempus felis eget accumsan. Fusce dictum eget turpis ut elementum. Integer massa nunc, convallis sed imperdiet quis, consectetur eget urna. Vivamus justo magna, tempor sit amet finibus sit amet, bibendum eu velit. Maecenas quis massa vel mi congue varius. Donec et enim luctus, interdum justo ac, scelerisque lectus. Etiam ac convallis risus. Cras pretium non est eu convallis. Ut aliquam tellus purus, ac pulvinar erat placerat eget. Vivamus varius nec ligula in placerat. Nulla facilisi. Nam ornare porttitor est quis congue. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos.</p>

                <p>Pellentesque non tempus augue. Fusce congue est et neque blandit rutrum vitae at massa. Duis luctus accumsan erat. Aenean placerat, nisl ac finibus porttitor, leo enim rutrum magna, in lacinia mi tellus vitae magna. Morbi pulvinar tristique varius. Morbi tincidunt tellus ut commodo placerat. Quisque ut dictum nulla. Pellentesque libero nisi, tincidunt eget vulputate vitae, pellentesque quis mi. Cras eu quam diam. Nulla dapibus, augue eget condimentum mattis, enim risus tempus massa, ac pulvinar orci nibh nec purus. Vestibulum ut pharetra nisl. Donec non commodo lorem. Proin sagittis augue leo, sed rutrum leo sollicitudin at. Nam nulla turpis, facilisis at nunc in, dapibus pellentesque massa.</p>

        </div>
    </main>

    <TheFooter />

</template>