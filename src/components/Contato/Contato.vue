<template>
    <div id="contato">
        <div>
        
        <div id="conteudo-contato">
            <div class="conteudos">
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
            <div class="conteudos">
                <h2>Horário de funcionamento</h2>
                <div class="itens-contato">
                    <img src="./clock 1.png" alt="relogio">
                    <p>Segunda a sabado - 6:00 às 21:00</p>
                </div>
            </div>
            <div>
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3950.410386945646!2d-34.905713285220166!3d-8.059554094196896!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x7ab18ded1bc6309%3A0xaf428d791ebffe71!2sEscola%20Polit%C3%A9cnica%20de%20Pernambuco!5e0!3m2!1spt-BR!2sbr!4v1596520281225!5m2!1spt-BR!2sbr" width="400" height="300" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
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
        font-size: 1rem;
    }
    .conteudos{
        margin-right: 1.5rem;
    }
    #conteudo-contato{
        display: flex;
        flex-direction: row;
        width: fit-content;
        padding-top: 5vh;
        margin-left: 1.5rem;
        margin-right: 1.5rem;
        /*padding-right: 1.5rem;*/
        justify-content: space-between;
        border-bottom: 1px solid black;
    }
    #conteudo-contato h2{
        text-align: left;
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
        text-align: left;
    }

    #redes-sociais{
        max-width: 95%;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
    }
    #redes-sociais p{
        text-align: left;
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
        width: 100%;
        padding-bottom: 2vh;
        padding-top: 2vh;
    }
    #rodape p{
        padding-left: 1.5rem;
    }
    #rodape img{
        width: 15%;
        padding-right: 1.5rem;
    }

    @media (max-width: 882px) {
        #conteudo-contato{
            flex-direction: column;
        }
    }
</style>