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
    <header>

        <section>
            <div class="header-nav">

                <div class="section-1">
                    <div class="logo">
                        <h1>
                            Uni 
                       </h1>
                            <h2>
                                Love 
                            </h2>
                    </div>

                    <div class="istituti">

                        <h3>
                            istituti
                        </h3>

                        <div class="dropdown">
                            <h3 class="dropdown-title">scuole superiori</h3>
                            <ul class="dropdown-menu">
                                <li><a href="#">Liceo Classico</a></li>
                                <li><a href="#">Liceo Scientifico</a></li>
                                <li><a href="#">Istituto Tecnico</a></li>
                                <li><a href="#">Istituto Professionale</a></li>
                            </ul>
                        </div>

                              <h3>
                                appunti
                              </h3>

                    </div>
                    
                
                </div>
                

                <div class="section-2">

                    <div class="register">

                        <div class="login-start">
                            <button class="button-login">
                                accedi
                            </button>

                            <div class="ita">

                                <div class="logo-ita">
                                      <img src="https://th.bing.com/th/id/R.4e9564569e476393bb80894c7803fc75?rik=FF4PI%2fKmZwgVoQ&pid=ImgRaw&r=0" alt="">
                                </div>

                            </div>
                        </div>

                    </div>

                </div>

            </div>
            

        </section>
        
        

    </header>
</template>

<style lang="scss" scoped>

.img{
    width: 100%;
}

h1{
    
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}



h2{
    color: #C21807;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}

.section-1{
    display: flex;
    justify-content: space-between;
    margin-left: 5px;
    margin-top: 0px;
    align-items: center;
    display: flex;
    gap: 50px;


}

.logo{
    display: flex;
    justify-content: space-between;
    margin-left: 5px;
    
}

.header-nav{
    display: flex;
    justify-content: space-between;
   
    align-items: center;
    width: 100%;
    
    height: 40px;
    
}

.istituti{
    margin-top: 0px;
    align-items: center;
    display: flex;
    gap: 30px;
}

.register {
    display: flex;
    justify-content: center;
    align-items: center;
    
}

.login-start{
    padding: 1px;
    display: flex;

}


.button-login {
    height: 30px;
    width: 80px;
    font-weight: bold;        
    color: #fff;             
    background-color: red; /* Colore di sfondo blu (puoi cambiarlo) */
    border: none;             /* Rimuove i bordi */
    border-radius: 8px;       /* Arrotonda gli angoli del pulsante */
    cursor: pointer;          /* Cambia il cursore in "punta di mano" */
    transition: background-color 0.3s ease, transform 0.2s ease; /* Animazione transizione */
    margin-right: 10px;       /* Aggiungi un margine a destra */
}


.button-login:hover {
    background-color: black; /* Cambia il colore di sfondo al passaggio del mouse */
    transform: scale(1.05);    /* Leggero ingrandimento del pulsante al passaggio del mouse */
    
}

.button-login:active {
    transform: scale(0.95);    /* Riduzione del pulsante al click per un effetto di feedback */
}
.dropdown {
    position: relative; 
    display: inline-block;
}

.dropdown-title {
    cursor: pointer; /* Cambia il cursore al passaggio del mouse */
    font-size: 18px;
    color: black;
    transition: color 0.3s ease;
}

.dropdown-title:hover {
    color: red; /* Cambia colore al passaggio del mouse */
}

.dropdown-menu {
    display: none; /* Nasconde il menu di default */
    position: absolute;
    background-color: #f9f9f9;
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
    padding: 12px;
    list-style: none;
    z-index: 1; /* Assicura che il menu sia sopra gli altri elementi */
}

.dropdown-menu li {
    padding: 8px 0;
}

.dropdown-menu li a {
    text-decoration: none;
    color: #333;
    padding: 8px;
    display: block;
}

.dropdown-menu li a:hover {
    background-color: red;
    color: white;
}

/* Mostra il menu quando l'utente passa con il mouse sulla title */
.dropdown:hover .dropdown-menu {
    display: block;
}

.ita {
    display: flex;            /* Flexbox per centrare l'immagine */
    justify-content: center;
    align-items: center;
    margin-top: 6px;
    width: 20px;              /* Imposta la larghezza del contenitore */
    height: 20px;             /* Imposta l'altezza del contenitore */
    margin-left: 5px;  
    margin-right: 5px;           /* Aggiungi un margine a sinistra */
}


.logo-ita img {
    width: 100%;              /* Imposta l'immagine al 100% della larghezza del suo contenitore */
    height: 100%;
    height: auto;             /* Mantieni le proporzioni dell'immagine */
    object-fit: contain;      /* Assicura che l'immagine si ridimensioni senza tagliarsi */
    
}



</style>
