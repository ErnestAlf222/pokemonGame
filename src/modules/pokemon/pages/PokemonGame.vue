<template>
    <section v-if="false" class="flex flex-col justify-center items-center w-screen h-screen">
        <h1 class="text-3xl">Espere por favor</h1>
        <h3 class="animate-pulse">Cargando Pokemons</h3>

    </section>

    <section class="flex flex-col justify-center items-center w-screen h-screen">
        <h1 class="m-5">¿Quién es este Pokemón?</h1>

        <!-- Pokemón Picture -->
        <PokemonPicture />

        <!-- Pokemón Options -->
        <PokemonOptions />

    </section>
</template>

<script setup>
import PokemonOptions from '../components/PokemonOptions.vue';
import PokemonPicture from '../components/PokemonPicture.vue';


</script>
