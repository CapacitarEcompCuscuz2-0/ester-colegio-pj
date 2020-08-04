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
            <button v-on:click="rolar">HOME</button>
            <button v-on:click="rolar">SOBRE</button>
            <button v-on:click="rolar">DEPOIMENTOS</button>
            <button v-on:click="rolar">RESULTADOS</button>
            <button v-on:click="rolarespecial"><router-link to="/Contato">CONTATO</router-link></button>
        </div>
    </div>
</template>

<script>
export default {
    name:'Menu',
    methods: {
        rolar : function(event) {
            var elemento = event.currentTarget
            var idAlvo = elemento.innerHTML.toLowerCase()
            var coord = document.getElementById(idAlvo).offsetTop

            if (idAlvo == 'home') {
                if (document.getElementById('contato-form') != null) {
                    coord -= document.getElementById('contato-form').offsetTop
                } else {
                    coord = 0
                }
            }
            
            window.scroll({
                top: coord,
                behavior: 'smooth',
            })
        },
        rolarespecial: function () {
            window.scroll({
                top: 0,
                behavior: 'smooth',
            })
        }
    }
}
</script>

<style scoped>
    #navbar{
        color: white;
        background-color: rgba(69, 65, 255, 0.8);
        position: fixed;
        top: 0;
        height: 13.4vh;
        width: 94%;
        padding-right: 3%;
        padding-left: 3%;
        display: flex;
        justify-content: space-between;
        align-items: center;
        z-index: 2;
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

    #menu button{
        background-color: transparent;
        border-color: transparent;
        color: white;
        cursor: pointer;
    }

    #menu a{
        text-decoration: none;
        color: white;
    }
</style>