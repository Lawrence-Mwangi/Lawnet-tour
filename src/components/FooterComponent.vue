<script setup></script>

<template>
    <div class="footer_container">
        <div class="footer_content">
            <div class="footer_infor">
                <img src="../assets/images/ocean.jpg" width="40px" height="40px" alt="logo Image">
                <p><span>Lawnet Tours & Travel</span> &#9989;</p>
                <p>We offer the best travel services. If you're planning to explore the world,
                    have inquiries, or need assistance, contact us.
                </p>
                <p>Kiambu, Kenya</p>
            </div>

            <div class="footer_links">
                <h3>Links</h3>
                <li><router-link :to="{ name:'home' }" >Home</router-link></li>
                <li><router-link :to="{ name:'about' }">About</router-link></li>
                <li><router-link :to="{ name:'service' }">Service</router-link></li>
            </div>
            
            <div class="footer_social">
                <h3>Social Media</h3>
                <a href="https://github.com/lawrencemwangi" target="_blank" rel="noopener noreferrer">
                    <img src="../assets/images/github.png" alt="github icon">
                </a>
                <a href="https://www.instagram.com/lawrenzo.mwangi/" target="_blank" rel="noopener noreferrer">
                    <img src="../assets/images/instagram.png" alt="instagram icon">
                </a>
                <a href="https://www.linkedin.com/in/lawrencemwangi/" target="_blank">
                    <img src="../assets/images/linkedin.png" alt="linkedin icon">
                </a>
                <a href="http://wa.me/254799509242?text='Hello Lawnet developers'" target="_blank" rel="noopener noreferrer">
                    <img src="../assets/images/whatsapp.png" alt="whatapp icon">
                </a>
            </div>
        </div>

        <hr>
        <div class="footer_copyrigth">
            <p>&copy; 2024 | Lawnet Tours And Travel | All Rigth Reserved</p>
        </div>
    </div>
</template>