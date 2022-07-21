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

            

            <h3 class="titulo-nosotros__contenido">Historia</h3>

            <p>Nam fringilla laoreet massa sit amet dignissim. Nulla in sapien egestas mauris gravida dignissim non ac est. Phasellus consectetur viverra ex eget facilisis. Maecenas id nisi eu leo porttitor viverra. Integer efficitur, neque id luctus tincidunt, leo enim iaculis elit, ac feugiat mauris sem ac quam. Morbi laoreet eget odio et facilisis. Pellentesque luctus tortor nisi, non placerat erat dignissim sed.</p>

            <p>Sed viverra ex vitae dolor viverra, quis pharetra turpis porttitor. Mauris consequat arcu quis nulla tempor facilisis. Nulla mi arcu, viverra in sodales sit amet, tempor id libero. In tempus sed tellus quis cursus. Phasellus placerat lobortis orci, ac feugiat justo volutpat ut. Suspendisse tristique sollicitudin faucibus. Vivamus vehicula pharetra sapien quis mollis. Nam at ultrices augue, congue aliquet enim. In ac erat sed felis hendrerit porttitor eu vitae lacus. Pellentesque eget pretium eros.</p>

            <p>Proin auctor enim a dictum feugiat. Nunc lectus arcu, finibus quis vehicula sed, laoreet nec magna. Donec cursus velit neque, ut dignissim turpis suscipit a. Phasellus quis nulla feugiat elit cursus lobortis ut vitae sem. Ut auctor lorem at tortor ullamcorper laoreet ac id erat. In volutpat enim ac felis pulvinar, at gravida mauris semper. Proin ultricies, enim vitae ullamcorper placerat, turpis nulla consectetur ligula, vel vestibulum urna libero quis ex. Donec a dolor luctus eros luctus tincidunt. Fusce vitae lacus ut urna pellentesque luctus. Pellentesque commodo lacus quis tortor vestibulum, at tincidunt diam viverra. Praesent finibus sit amet nibh sit amet consequat. Sed eu est lorem. Quisque facilisis massa quis dui mollis, fringilla mattis ante tincidunt. Praesent blandit venenatis facilisis. Ut tristique justo in ipsum consequat, quis placerat lacus mattis.</p>

            <p>Maecenas aliquet nibh tempus suscipit pharetra. Pellentesque dignissim magna in elit pellentesque aliquet. Aenean non viverra arcu. Duis rhoncus arcu at ante volutpat rutrum. Sed accumsan est nibh, vitae maximus ipsum semper vel. Nulla ullamcorper augue non ipsum consequat, id tristique erat rhoncus. Vivamus luctus velit non aliquam sodales. Phasellus ut mi dapibus, venenatis nisi ut, volutpat lectus. Quisque lacinia finibus posuere. Quisque ultricies suscipit odio, non aliquet elit tempus vel. Nunc non tempor neque. Praesent nec erat ac mauris placerat commodo. Aenean ut cursus sapien.</p>

            <p>Sed sagittis urna vitae metus vestibulum pellentesque. Ut rhoncus, tortor sit amet maximus congue, justo dui tincidunt metus, ut consequat dui eros efficitur ligula. Pellentesque vehicula sagittis nibh eget gravida. Proin nec velit vel ante bibendum sollicitudin in ut arcu. Quisque at velit dapibus, fermentum libero nec, accumsan nisl. Praesent vel urna facilisis, tincidunt urna ut, porta lectus. Pellentesque ac pellentesque nisl, a convallis neque. Nullam ut scelerisque nibh. Donec elit lectus, pellentesque nec eleifend sit amet, ornare convallis lorem. Sed tempus metus nec neque gravida fermentum. Etiam velit massa, sagittis sed laoreet ut, mollis id diam. In convallis feugiat rutrum. Curabitur dolor risus, sagittis eu ligula non, eleifend fermentum magna. Fusce eu commodo magna. Vivamus dolor tellus, pellentesque iaculis porta sit amet, eleifend ut sem. Nulla consequat lacinia arcu non sodales.</p>

            <p>Integer vestibulum nisi sed finibus vehicula. Nullam ullamcorper sed nibh vitae sodales. Quisque a pellentesque est. Aliquam sit amet tristique turpis. Vestibulum mi dui, porttitor ut tincidunt non, cursus id tortor. Curabitur eget aliquam purus. Donec molestie ante et enim porttitor euismod. Vestibulum elementum felis elit, in varius mauris sollicitudin quis. Aliquam bibendum arcu eu bibendum pulvinar. Sed mollis purus vel massa malesuada gravida. Nulla semper nisl sollicitudin diam sollicitudin ultricies.</p>

            <p>Aenean feugiat sagittis velit. In porta maximus efficitur. Vestibulum pharetra facilisis malesuada. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus aliquet vel felis sed condimentum. Aliquam aliquet porttitor lobortis. Proin in purus hendrerit, vehicula purus eu, malesuada erat. Donec pretium massa ut sapien dictum varius. Aliquam vitae mi ut enim ultricies volutpat. Curabitur eget metus ac est maximus vulputate id vel erat. Donec porta ultrices tincidunt. Nam vitae tortor ante.</p>

        </div>
    </main>

    <TheFooter />

</template>