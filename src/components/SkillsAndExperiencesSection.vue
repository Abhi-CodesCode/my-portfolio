<template>
    <section class="text-white mt-18" id="skills">
        <div class="absolute right-0 top-[110rem] h-full w-full justify-end">
            <span class="flex opacity-20">
                <span class="w-16 h-32 rounded-l-full flex bg-primary blur-2xl"></span>
                <span class="w-16 h-32 rounded-r-full flex bg-[#f88fc2] blur-2xl mt-14"></span>
            </span>
        </div>
        <div class="grid grid-cols-2 gap-8 items-center py-8 px-4 xl:gap-16 xl:px-16">
            <div class="mt-4 md:mt-0 text-left flex flex-col z-10 h-full w-[80%]">
                <h2 class="text-4xl font-bold text-white text-left mb-4">My
                    <span class="text-transparent bg-clip-text bg-gradient-to-r from-primary to-secondary">Skills</span>
                </h2>
                <div class="mt-8" v-for="skill in skills":key="skill.id">
                    <div class="flex items-end justify-between" data-aos="fade-right">
                        <h4 class="font-semibold uppercase text-white">
                            {{ skill.skill }}
                        </h4>
                        <h3 class="text-2xl font-bold text-white">{{ skill.level }}</h3>
                    </div>
                    <div class="h-1 rounded-full bg-primary" :style="{ width: skill.level }"></div>
                </div>
            </div>
        
        <div data-aos="flip-left">
            <h2 class="text-4xl font-bold text-white text-left mb-8 md:text-center md:mt-0 mt-8">My Experiences</h2>
            <div class="space-y-8 py-8" data-aos="fade-left">
                <div v-for="element in experiences" :key="element.id" class="flex items-center rounded-xl p-4 bg-[#111a3e] shadow-lg border-[#1f1641]">
                    <div class=" w-1/4">
                        <img src="https://img.icons8.com/?size=100&id=BGVD49kNT0LA&format=png&color=ffffff" alt="job-icon" >
                    </div>
                    <div class=" w-3/4 justify-between items-center">
                        <h3 class="text-2xl font-semibold uppercase text-transparent bg-clip-text bg-gradient-to-r from-primary to-secondary">
                            {{ element.role }}
                        </h3>
                        <p class="text-white">{{ element.company }}</p>
                        <p class="text-white">{{ element.date }}</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    </section>
</template>
<script setup>
import { ref } from 'vue';
const skills = ref([
    {
        id: 1,
        skill: 'HTML',
        level: '90%'
    },
    {
        id: 2,
        skill: 'CSS',
        level: '80%'
    },
    {
        id: 3,
        skill: 'JavaScript',
        level: '70%'
    },
    {
        id: 4,
        skill: 'Vue.js',
        level: '60%'
    },
        {
        id: 3,
        skill: 'JavaScript',
        level: '70%'
    },
    {
        id: 4,
        skill: 'Vue.js',
        level: '60%'
    },
])
const experiences = ref([
    {
        id: 1,
        role: 'App Developer',
        company: 'Self-Employed',
        date:'May 2021 - Present',
    },
    {
        id: 2,
        role: 'Web Developer',
        company: 'Self-Employed',
        date:'May 2021 - Present',
    },
])


</script>
