<template>
<div id="contato-form">
    <div>
        <h1>FALE CONOSCO</h1>
        <p>Envie uma mensagem para nossa equipe e contataremos você!</p>
    </div>
    <div id=formulario>
        <form action="/" enctype="text/plain">
        <div id="infospessoais">
            <label for="nome">Nome completo:</label>
            <input type="text" name="nome" id="nome"><br>
            <label for="email">E-mail:</label>
            <input type="email" name="email" id="email"><br>
        </div>
            <label for="msg">Sua mensagem:</label>
            <input type="text" name="msg" id="msg"><br>
            <input type="submit" value="Enviar">
        </form>
    </div>
</div>
</template>

<style scoped>
    #contato-form{
        background-color: #EAE1E1;
        width: 100%;
        height: 86.5vh;
        padding-top: 8vh;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-items: center;
        font-size: 1.5rem;
    }

    #formulario{
        height: 40vh;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    #contato-form form{
        display: flex;
        flex-direction: row;
        text-align: left;
    }

    #infospessoais{
        display: flex;
        flex-direction: column;
        margin-right: 5vw;
    }

    #infospessoais input{
        margin-bottom: 2vh;
    }

    #formulario form label{
        margin-right: 1vw;
    }
</style>