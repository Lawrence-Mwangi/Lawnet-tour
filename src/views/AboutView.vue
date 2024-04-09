<script setup>
import Navbar from '@/components/NavbarComponent.vue'
import Footer from '@/components/FooterComponent.vue'

</script>


<template>
    <Navbar/>

    <div class="main_container">
        <h1>About Us</h1>

        <div class="about_container">
            <div class="about_content">
                <div class="about_items">
                    <p>Founded in 2022, Lanwnet Tours and Travel started as a humble family venture and swiftly burgeoned into a global entity.
                        Specializing in personalized and immersive travel experiences, it has become synonymous with exceptional service and unforgettable
                        adventures across the globe.
                    </p>
                </div>
                <div class="about_image">
                    <img src="../assets/images/beach1.jpg" alt="about Image">
                </div>
            </div>

            <h2>Our Founder</h2>
            <div class="founder">
                <p>Lawrence, founder of Lanwnet Tours and Travel, ignited his passion for exploration early on. Starting from scratch in 2022,
                    his vision transformed into a global enterprise, driven by a commitment to deliver personalized and memorable travel
                    experiences worldwide.
                </p>
                <div class="founder_image">
                    <img src="../assets/images/image1.jpg" alt="Lawrence Image">
                    <div class="infor">
                        <p>Founder & CEO <span> (Lawnet Tours & Travel)</span></p>
                        <p>Lawrence Mwangi</p>
                    </div>
                </div>
            </div>
        </div>
    </div>


    <Footer/>
</template>