<template>
    <div id="sobre">
        <p>SOBRE</p>
        <img src="./pencil 1.png" alt="lapis">
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempo incididunt
            ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
            ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in
            reprehendrit in voluptate vellit esse cillum dolore eu fugiat nulla pariatur. Excepteur
            sint occaecat cupidatat non proident,sunt in culpa qui officia deserunt mollit anim id
            est laborum.
        </p>
    </div>
</template>

<style scoped>
    #sobre{
        color: white;
        background-color:rgba(69, 65, 255, 0.75);
        text-align: center;
        height: 86.6vh;
        width: 100%;
        padding-top: 13.4vh;
        display: flex;
        flex-direction: column;
        justify-content: space-evenly;
        align-items: center;
    }

    #sobre :nth-child(1){
        margin: 0;
        width: 13%;
        font-size: 6.7vh;
    }

    #sobre img{
        width: 7.3%;
    }

    #sobre :nth-child(3){
        margin: 0;
        width: 71%;
        font-size: 3.3vh;
    }
</style>