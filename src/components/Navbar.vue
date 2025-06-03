<template>
    <header class="bg-white shadow-sm top-0 z-50">
        <div class="max-w-6xl mx-auto flex items-center justify-between px-6 py-4">
            <h1 class="text-xl font-bold text-indigo-700">
                FitStart
            </h1>

            <!-- Desktop nav -->
            <nav class="hidden md:flex items-center gap-6 text-gray-600 font-medium">
                <a href="#servizi" class="hover:text-indigo-600 transition">Servizi</a>
                <a href="#testimonianze" class="hover:text-indigo-600 transition">Testimonianze</a>
                <a href="#contatti" class="hover:text-indigo-600 transition">Contatti</a>
            </nav>

            <!-- Mobile hamburger -->
            <button class="md:hidden" @click="isOpen = !isOpen">
                <svg class="w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                </svg>
            </button>
        </div>

        <!-- Mobile menu -->
        <div v-if="isOpen" class="md:hidden px-6 pb-4 space-y-3">
            <a href="#servizi" class="block text-gray-700">Servizi</a>
            <a href="#testimonianze" class="block text-gray-700">Testimonianze</a>
            <a href="#contatti" class="block text-gray-700">Contatti</a>
        </div>
    </header>
</template>

<script setup>
import { ref } from 'vue'
const isOpen = ref(false)
</script>
