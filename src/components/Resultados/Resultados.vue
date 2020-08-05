<template>
    <div id="resultados">
        <h1>RESULTADOS</h1>
        <div id="transparente">
            <p>
                1º LUGAR NO ENEM ENTRE OS COLÉGIOS DE TODO O BRASIL    
            </p>
            <p>
                10 PRIMEIROS LUGARES DO SSA
            </p>
            <p>
                APROVAÇÕES EM FACULDADES DE TODO O PAÍS
            </p>
        </div>
    </div>
</template>

<style scoped>
    #resultados{
        background-color: #EAE1E1;
        width: 100%;
        height: 86.6vh;
        padding-top: 13.4vh;
        font-size: 1.6rem;
        display: flex;
        flex-direction: column;
        align-items: center;
        overflow: hidden;
    }
    #resultados h1{
        margin: 0;
        padding-top: 4vh;
        padding-bottom: 4vh;
        color: #4541FF;
        text-align: center;
    }
    
    #transparente{
        background-image: url("./university 3.png");
        background-repeat: no-repeat;
        background-position: center center;
        background-size: 32vw;
        background-color: rgba(0, 0, 0, 0.2);
        border-radius: 50px;
        padding: 3vh 2vh 3vh 2vh;
        height: 53vh;
        width: 88%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        text-align: justify;
        font-size: 2.9rem;
    }
    #transparente :nth-child(1) {
        margin: 0;
        color: #4541FF;
    }
    #transparente :nth-child(2) {
        margin: 0;
        color: white;
    }
    #transparente :nth-child(3) {
        margin: 0;
        color: black;
    }
</style>