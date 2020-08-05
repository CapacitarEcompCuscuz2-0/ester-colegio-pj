<template>
    <div id="depoimentos">
            <h1>DEPOIMENTOS</h1>
            <div id="alunos-e-txts">
                <div id="book">
                    <div class="dep-esquerda">
                        <img class="img-alunos" src="./aluno1.png" alt="aluno1">
                        <div class="dep-texto">
                            <h3>Nome do ex aluno</h3>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempo
                                incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
                                nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                                Duis aute irure dolor in reprehendrit in voluptate vellit esse cillum dolore
                                eu fugiat nulla pariatur.
                            </p>
                        </div>
                    </div>
                    <div class="dep-direita" id="do-meio">
                        <img class="img-alunos" src="./aluno2.png" alt="aluno2">
                        <div class="dep-texto">
                            <h3>Nome do ex aluno</h3>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempo
                                incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
                                nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                                Duis aute irure dolor in reprehendrit in voluptate vellit esse cillum dolore
                                eu fugiat nulla pariatur.
                            </p>
                        </div>
                    </div>
                </div>
                <div id="pencil">
                    <div class="dep-esquerda">
                        <img class="img-alunos" src="./aluno3.png" alt="aluno3">
                        <div class="dep-texto">
                            <h3>Nome do ex aluno</h3>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempo
                                incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
                                nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                                Duis aute irure dolor in reprehendrit in voluptate vellit esse cillum dolore
                                eu fugiat nulla pariatur.
                            </p>
                        </div>
                    </div>
                    <div class="dep-direita">
                        <img class="img-alunos" src="./aluno4.png" alt="aluno4">
                        <div class="dep-texto">
                            <h3>Nome do ex aluno</h3>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempo
                                incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
                                nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                                Duis aute irure dolor in reprehendrit in voluptate vellit esse cillum dolore
                                eu fugiat nulla pariatur.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
</template>

<style scoped>
    #depoimentos{
        color: #4541FF;
        background-color: #EAE1E1;
        height: 330vh;
        width: 100%;
        padding-top: 13.4vh;
        display: flex;
        flex-direction: column;
        align-items: center;
        font-size: 1.6rem;
    }

    p{
        font-size: 1.4rem;
    }

    #book{
        background-image: url("./book 1.png");
        background-repeat: no-repeat;
        background-size: 60vw;
        background-position: 55% 35%;
    }

    #pencil{
        background-image: url("./pencil 2.png");
        background-repeat: no-repeat;
        background-size: 50vw;
        background-position: 55% 35%;
    }

    #alunos-e-txts{
        width: 84.8vw;
    }

    #depoimentos h1{
        margin: 0;
        padding-top: 4.4vh;
        padding-bottom: 4.4vh;
    }

    #depoimentos h3{
        max-width: fit-content;
    }

    .img-alunos{
        width: 33.8%;
    }

    .dep-texto{
        text-align: justify;
        width: 63%;
    }

    .dep-esquerda{
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        border-bottom: 3px solid #4541FF;
    }

    .dep-direita{
        display: flex;
        flex-direction: row-reverse;
        justify-content: space-between;
        align-items: center;
    }

    #do-meio{
        border-bottom: 3px solid #4541FF;
    }

    .dep-texto p{
        color: #5F5858;
    }
</style>