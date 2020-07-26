<template>
    <div id="contato">
            <div id="conteudo-contato">
                <div>
                    <h2>Entre em contato</h2>
                    <div class="itens-contato">
                        <img src="./maps-and-flags.png" alt="checkin">
                        <p>R. Benfica, 455 - Madalena,<br>Recife - PE<br>CEP: 50720-001</p>
                    </div>
                    <div class="itens-contato">
                        <img src="./email.png" alt="email">
                        <p>colegio@polijr.com.br</p>
                    </div>
                    <div class="itens-contato">
                        <img src="./call.png" alt="fone">
                        <p>81 3344-5566</p>
                    </div>
                    <div class="itens-contato">
                        <img src="./whatsapp.png" alt="whatsapp">
                        <p>81 996158406</p>
                    </div>
                </div>
                <div>
                    <h2>Horário de funcionamento</h2>
                    <div class="itens-contato">
                        <img src="./clock 1.png" alt="relogio">
                        <p>Segunda a sabado - 6:00 às 21:00</p>
                    </div>
                </div>
                <div>
                    <img id="img-mapa" src="./Captura de Tela (1) 1.png" alt="mapa">
                    <div id="redes-sociais">
                        <p>Clique nos ícones<br>para acessá-los</p>
                        <a href="https://www.youtube.com/" target="_blank">
                            <img id="testetamanho" src="./youtube 1.png" alt="youtube">
                        </a>
                        <a href="https://www.facebook.com/" target="_blank">
                            <img src="./facebook.png" alt="facebook">
                        </a>
                        <a href="https://www.twitter.com/" target="_blank">
                            <img src="./twitter.png" alt="twitter">
                        </a>
                        <a href="https://www.instagram.com/" target="_blank">
                            <img src="./instagram 1.png" alt="instagram">
                        </a>
                    </div>
                </div>
            </div>
            <div id="rodape">
                <p>© 2020 Todos os direitos reservados – Colégio Poli Jr</p>
                <img src="./índice.png" alt="logo-polijr">
            </div>
        </div>
</template>

<style scoped>
    #contato{
        background-color: #EAE1E1;
        width: 100%;
        height: 86.6vh;
        padding-top: 13.4vh;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: space-between;
        font-size: 1em;
    }

    #conteudo-contato{
        display: flex;
        flex-direction: row;
        width: 80vw;
        padding-top: 5vh;
        justify-content: space-between;
    }

    .itens-contato{
        color: #5F5858;
        display: flex;
        align-items: flex-start;
    }

    .itens-contato img{
        height: 100%;
        padding-right: 1vw;
    }

    .itens-contato p{
        margin: 0;
        margin-bottom: 1vh;
    }

    #img-mapa{
        width: 25vw;
    }

    #redes-sociais{
        max-width: 95%;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
    }

    #redes-sociais a img{
        width: 170%;
        height: max-content;
    }

    #rodape{
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        width: 80vw;
        padding-bottom: 5vh;
        padding-top: 3vh;
        border-top: 1px solid black;
    }

    #rodape img{
        width: 15%;
    }
</style>