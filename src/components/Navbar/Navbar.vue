<template>
    <div id="navbar">
        <div id="logo">
            <img src="./university 4.png" alt="logo">
            <div id="logo-texto">
                <div>Colégio</div>
                <div>Poli Jr</div>
            </div>
        </div>
        <div id="menu">
            <a href="#home"><p>HOME</p></a>
            <a href="#sobre"><p>SOBRE</p></a>
            <a href="#depoimentos"><p>DEPOIMENTOS</p></a>
            <a href="#resultados"><p>RESULTADOS</p></a>
            <a href="#contato"><p>CONTATO</p></a>
        </div>
    </div>
</template>

<style scoped>
    #navbar{
        color: white;
        background-color: rgba(69, 65, 255, 0.8);
        position: fixed;
        height: 13.4vh;
        width: 94%;
        padding-right: 3%;
        padding-left: 3%;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    #logo{
        height: 100%;
        width: auto;
        display: flex;
        flex-direction: row;
    }

    #logo img{
        height: 100%;
    }

    #logo-texto{
        padding-left: 10%;
        text-align: left;
        display: flex;
        justify-content: center;
        flex-direction: column;
    }

    #logo-texto :nth-child(1){
        font-size: 0.9rem;
    }

    #logo-texto :nth-child(2){
        width: max-content;
        font-size: 1.8rem;
    }

    #menu{
        width: 60%;
        font-size: 3.2vh;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
    }

    #menu a:visited, a:link, a:active, a:hover{
        text-decoration: none;
        color: white;
    }
</style>