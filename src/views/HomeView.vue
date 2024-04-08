<script setup>
import Navbar from '@/components/NavbarComponent.vue'
import Hero from '@/views/HeroView.vue'
import Project from '@/views/projectView.vue'
import Design from '@/views/DesignView.vue'
import Contact from '@/views/ContactView.vue'
import Footer from '@/components/FooterComponent.vue'
</script>

<template>

    <navbar/>

    <section class="hero_content" id="Hero">
    <Hero/>
    </section>

    <section class="main_container" id="project">
        <Project/>
    </section>

    <section class="main_container" id="Design">
        <Design/>
    </section>

    <section class="main_container" id="Contact">
        <Contact/>
    </section>

    <Footer/>
</template>
