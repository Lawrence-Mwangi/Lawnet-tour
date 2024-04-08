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
                    <p>Welcome to LawNet Tour and Travel! Founded in 2022, we specialize in providing exceptional legal-themed virtual reality experiences.
                        Our immersive simulations and educational content redefine legal education and entertainment. Join us as we lead the way in shaping 
                        the future of legal VR. Embark on an unforgettable journey with LawNet.
                    </p>
                </div>
                <div class="about_image">
                    <img src="../assets/images/beach1.jpg" alt="about Image">
                </div>
            </div>

            <h2>Our Founder</h2>
            <div class="founder">
                <p>Lawrence, the visionary owner of LawNet Tour and Travel, is a dedicated technologist with a passion for pushing the boundaries of virtual reality.
                    With a background in law and a keen interest in technology, Lawrence brings a unique perspective to the company, driving innovation and excellence 
                    in every aspect of its operations.
                </p>
                <div class="founder_image">
                    <img src="../assets/images/image1.jpg" alt="Lawrence Image">
                    <div class="infor">
                        <p>Founder & CEO (lawnet Tours & Travel)</p>
                        <p>Lawrence Mwangi</p>
                    </div>
                </div>
            </div>
        </div>
    </div>


    <Footer/>
</template>