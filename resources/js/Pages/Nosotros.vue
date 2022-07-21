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

        <div class="contenedor-nosotros sombra">

            <h3 class="titulo-nosotros__contenido">¿Quiénes somos?</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur pharetra elit eu velit convallis semper. Donec scelerisque risus eget metus vestibulum accumsan. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Duis eu diam nulla. Fusce non leo malesuada, iaculis metus eu, dapibus leo. Aenean ac sollicitudin arcu, ut rutrum libero. Sed ut libero sodales, pulvinar enim eu, sollicitudin erat.</p>

                <img src="@/../img/ejemplo-quienes-somos.jpg">

                <p>Curabitur ullamcorper fringilla ipsum, a tempor augue suscipit at. Sed luctus orci mollis lacus fermentum aliquet. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nam non scelerisque sapien. Aliquam condimentum congue varius. Vivamus vitae placerat tortor. Proin hendrerit risus vel felis vehicula tristique. Sed faucibus diam eget ornare sollicitudin. Curabitur congue aliquet arcu, a vestibulum tortor pellentesque eget. Pellentesque nisi orci, gravida a pharetra eget, tristique id nibh.</p>

                <p>Fusce non libero quis turpis vehicula volutpat. Mauris non sem placerat, accumsan augue in, rutrum nulla. Nunc mattis lectus a neque pulvinar dapibus. Pellentesque ultrices tincidunt vulputate. Sed sed metus velit. Aenean tortor leo, tincidunt at sem eu, imperdiet blandit tellus. Etiam commodo imperdiet est nec vulputate. Phasellus quis neque ut arcu volutpat cursus. Sed et dapibus velit. Ut aliquam lorem at purus pellentesque pellentesque. Maecenas fringilla, ipsum sit amet porttitor cursus, nunc lacus condimentum nisl, eget feugiat erat urna semper justo. Sed pharetra interdum tempor. Duis id massa ut justo suscipit euismod. Vestibulum nec tellus arcu. Maecenas rutrum nisi vel interdum viverra. Quisque massa ex, ullamcorper ultrices consequat eu, ullamcorper at est.</p>
        
        </div>
    </main>

    <TheFooter />

</template>

<style>
    .menu-nosotros{
        display: flex;
        justify-content: space-evenly;
        color: var(--primario);
    }
    .menu-nosotros-item{
        text-decoration: none;
        border: solid;
        border-radius: 5px;
        border-width: 1px;
        padding: 5px;
    }

</style>