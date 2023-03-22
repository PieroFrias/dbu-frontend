<template>
    <header class="bg-white shadow h-16 flex justify-between items-stretch">
        <router-link :to="{ name: 'home' }" class="inline-flex items-center h-full px-5">
            Home
        </router-link>
        <!-- <div class="flex items-center gap-1">
            <router-link :to="{ name: 'home' }"
                class="inline-flex items-center px-2 h-full transition-colors hover:bg-purple-100">
                Inicio
            </router-link>
            <router-link :to="{ name: 'salud' }"
                class="inline-flex items-center px-2 h-full transition-colors hover:bg-purple-100">
                Salud
            </router-link>
            <router-link :to="{ name: 'asistencias' }"
                class="inline-flex items-center px-2 h-full transition-colors hover:bg-purple-100">
                Asistencias
            </router-link>
        </div> -->
    </header>
</template>