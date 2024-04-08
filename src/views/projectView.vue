<script setup></script>

<template>
    <div class="project_container">
        <h1>Our Projects</h1>

        <div class="project_content">
            <div class="project_items">
                <div class="details">
                    <h2>Why Us</h2>
                    <p>LawNet Tours provides personalized legal tours, offering exclusive insights tailored to your interests. 
                        Explore the legal world with expertise and gain unique perspectives on your journey through immersive experiences.
                    </p>
                </div>

                <div class="details">
                    <h2>Lawnet Tours</h2>
                    <p>Opt for LawNet Tours for an unparalleled blend of legal expertise and personalized service. Gain exclusive access to the legal world,
                        tailored to your interests and needs, ensuring an exceptional and insightful journey every step of the way.
                    </p>
                </div>
            </div> 
        </div>

        <h2>Our Tours</h2>
        <div class="project_infor">
            <div class="work">
                <img src="../assets/images/wheel.jpg" alt="project Image">
                <h3>Ferris wheel</h3>
                <p>The Ferris wheel, an iconic symbol of fun and adventure, promises an unforgettable experience high above the bustling cityscape</p>
                <p>Price: <span>Ksh. 1,500</span></p>
                <div class="btn">
                    <button type="submit"><router-link :to="{ name:'service'}">Book Now</router-link> </button>
                </div>
            </div>

            <div class="work">
                <img src="../assets/images/maasaimara.jpg" alt="project Image">
                <h3>Maasai Mara National Reserve</h3>
                <p>Iconic savanna landscape teeming with wildlife, including lions, elephants, and wildebeest during migration</p>
                <p>Price: <span>Ksh. 10,500</span></p>
                <div class="btn">
                    <button type="submit"><router-link :to="{ name:'service'}">Book Now</router-link> </button>
                </div>
            </div>

            <div class="work">
                <img src="../assets/images/beach.jpg" alt="project Image">
                <h3>Dian Beach</h3>
                <p>Enjoy a trip to Diani beach in the coast of kenya and get to enjoy the beauty of the coast and ride boat and experience</p>
                <p>Price: <span>Ksh. 12,000</span></p>
                <div class="btn">
                    <button type="submit"><router-link :to="{ name:'service'}">Book Now</router-link> </button>
                </div>
            </div>
        </div>
    </div>
</template>