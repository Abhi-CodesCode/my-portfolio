<template>
    <section class="text-white mt-20" id="services">
        <div class="px-4 xl:pl-16">
            <h2 class="text-4xl font-bold text-white mb-4">My Services</h2>
        </div>
        <div class="py-8 xl:px-16 px-4 sm:py-16 grid grid-cols-1 gap-6 pt-10 sm:grid-cols-2 md:gap-10 md:pt-12 lg:grid-cols-3">
            <div v-for="service in services" :key="service.id" data-aos="fade-up" class="px-8 py-12 rounded-xl bg-[#111a3e] shadow-lg border border-[#1f1641]">
                <div class="mx-auto h-24 text-center xl:h-28 xl:w-28">
                    <div>
                        <img :src="service.icon" alt="service-icon" width="200"/>
                    </div>
                </div>
                <div class="text-center">
                    <h3 class="pt-8 text-lg font-semibold uppercase text-transparent bg-clip-text bg-gradient-to-r from-primary to-secondary lg:text-xl">
                        {{ service.name }}
                    </h3>
                    <p class="text-grey pt-4 text-sm group-hover:text-white md:text-base">{{ service.description }}</p>
                </div>
            </div>
        </div>

        
    </section>
</template>

<script setup>
import { ref, onMounted } from 'vue';
import AOS from 'aos';
import 'aos/dist/aos.css';
const services=ref([
    {
        id:1,
        icon:'https://img.icons8.com/ios-filled/100/ffffff/google-code.png',
        name:'Web Development',
        description:'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Maxime, ex labore.'
    },
    {
        id:2,
        icon:'https://img.icons8.com/?size=100&id=aghhDejBO0Am&format=png&color=ffffff',
        name:'App development',
        description:'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Maxime, ex labore.'
    },
    {
        id:3,
        icon:'https://img.icons8.com/?size=100&id=TAH7mJxpBhnm&format=png&color=ffffff',
        name:'Technical Writing',
        description:'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Maxime, ex labore.'
    },
    {
        id:4,
        icon:'https://img.icons8.com/?size=100&id=PhZcqNXjSCWl&format=png&color=ffffff',
        name:'Backend Development',
        description:'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Maxime, ex labore.'
    },
    {
        id:5,
        icon:'https://img.icons8.com/?size=100&id=aghhDejBO0Am&format=png&color=ffffff',
        name:'App development',
        description:'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Maxime, ex labore.'
    },
    {
        id:6,
        icon:'https://img.icons8.com/?size=100&id=TAH7mJxpBhnm&format=png&color=ffffff',
        name:'Technical Writing',
        description:'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Maxime, ex labore.'
    },

])

onMounted(() => {
    AOS.init();
});

</script>
