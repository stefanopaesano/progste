<script>
export default {
    data() {
        return {

        };
    },
    methods: {

    }
}
</script>

<template>
    <footer class="footer">
        <div class="footer-content">
            <!-- Logo e descrizione breve -->
            <div class="footer-logo">
                <h4>UniLove</h4>
                <p>La tua piattaforma di apprendimento connesso, semplice e sicuro.</p>
            </div>

            <!-- Collegamenti rapidi -->
            <div class="footer-links">
                <h4>Collegamenti Rapidi</h4>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Trova un Tutor</a></li>
                    <li><a href="#">Servizi</a></li>
                    <li><a href="#">Contattaci</a></li>
                </ul>
            </div>

            <!-- Contatti -->
            <div class="footer-contact">
                <h4>Contatti</h4>
                <p>Email: info@UniLove.com</p>
                <p>Telefono: +39 123 456 789</p>
            </div>

            <!-- Social media -->
            <div class="footer-social">
                <h4>Seguici</h4>
                <div class="social-icons">
                    <a href="#"><img src="https://img.icons8.com/fluency/48/ffffff/facebook-new.png" alt="Facebook" /></a>
                    <a href="#"><img src="https://img.icons8.com/fluency/48/ffffff/instagram-new.png" alt="Instagram" /></a>
                    <a href="#"><img src="https://img.icons8.com/fluency/48/ffffff/twitter-squared.png" alt="Twitter" /></a>
                </div>
            </div>
        </div>
        <div class="footer-bottom">
            <p>&copy; 2023 Studoku. Tutti i diritti riservati.</p>
        </div>
    </footer>
</template>

<style lang="scss" scoped>

.footer {
    background-color: #343a40;
    color: #fff;
    padding: 40px 20px 20px;
    text-align: center;
    font-family: Arial, sans-serif;

    .footer-content {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
        gap: 20px;
        padding-bottom: 20px;
        border-bottom: 1px solid #495057;
    }

    .footer-logo {
        text-align: center;
        img {
            width: 50px;
            margin-bottom: 10px;
        }
        p {
            max-width: 200px;
            margin: auto;
            font-size: 14px;
            line-height: 1.5;
        }
    }

    .footer-links, .footer-contact, .footer-social {
        h4 {
            margin-bottom: 10px;
            font-size: 18px;
            color: #f8f9fa;
        }
        ul {
            list-style-type: none;
            padding: 0;
            a {
                color: #adb5bd;
                text-decoration: none;
                transition: color 0.3s;
            }
            a:hover {
                color: #fff;
            }
            li {
                margin: 8px 0;
            }
        }
        p {
            font-size: 14px;
            color: #adb5bd;
        }
    }

    .footer-social .social-icons {
        display: flex;
        gap: 15px;
        justify-content: center;
        a {
            display: inline-block;
            img {
                width: 32px;
                height: 32px;
            }
        }
    }

    .footer-bottom {
        margin-top: 20px;
        font-size: 14px;
        color: #adb5bd;
    }
}

</style>
