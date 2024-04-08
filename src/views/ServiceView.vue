<script setup>
import Navbar from '@/components/NavbarComponent.vue'
import Footer from '@/components/FooterComponent.vue'

</script>

<template>
    
    <Navbar/>

    <div class="main_container">
        <div class="service_container">
            <h1>Service</h1>
            <h2>It's Time to Start Your Adventures</h2>
            <span></span>
            <p>Our comprehensive tours provide immersive experiences in diverse activities such as hiking, trekking, cultural tours, 
                wildlife safaris, rock climbing, and more, tailored to individual preferences for unforgettable adventures.
            </p>
            <div class="service_items">
                <div class="service_content">
                    <h3>hiking</h3>
                    <p>Experience nature's beauty and adventure through invigorating hikes in scenic landscapes,
                        offering tranquility and breathtaking views.
                    </p>
                </div>

                <div class="service_content">
                    <h3>wildlife Safaris</h3>
                    <p>Wildlife safaris offer immersive journeys into natural habitats, providing
                        opportunities to observe and photograph diverse animal species in their environment.
                    </p>
                </div>

                <div class="service_content">
                    <h3>Cultural Tour</h3>
                    <p>Cultural tours immerse travelers in local traditions, history, arts, 
                        and cuisine, fostering cross-cultural understanding and enriching experiences.
                    </p>
                </div>

                <div class="service_content">
                    <h3>Rock Climbing</h3>
                    <p>Rock climbing involves ascending natural or artificial rock formations using ropes 
                        and specialized equipment, offering physical challenges and breathtaking views.
                    </p>
                </div>
            </div>
        </div>
    </div>

    <Footer/>
</template>