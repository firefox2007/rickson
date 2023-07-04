root {
    --main-cinza: #CCCCCC;
    --main-branco: #FFFFFF;
    --main-preto: #000000;
}

* {
    box-sizing: border-box;
}

body {
    background: url(../img/fundo.jpg);
    background-position: center center;
    background-size: cover cover;
    padding: 0;root {
    --main-cinza: #CCCCCC;
    --main-branco: #FFFFFF;
    --main-preto: #000000;
}

* {
    box-sizing: border-box;
}

body {
    background: url(../img/fundo.jpg);
    background-position: center center;
    background-size: cover cover;
    padding: 0;
    margin: 0;
    font-weight: 300;
}

body, input {
    font-family: 'Teko', sans-serif;
}

main {
    width: 80vw;
    height: 80vh;
    margin: 10vh 8vw 10vh 12vw;
    display: flex;
    gap: 1vw;
}

.robotron {
    background: url(../img/estrutura.png) no-repeat;
    background-position: center center;
    margin: 0;
    flex-basis: 40%;
    position: relative;
}

.robo {
    height: 110%;
    z-index: 1;
    position: absolute;
    left: -20%;
    top: -5%;
}

.titulo {
    transform: rotate(180deg);
    font-weight: 500;
    font-size: 130px;
    position: absolute;
    bottom: 7rem;
    left: -3rem;
    line-height: 0.8;
    writing-mode: vertical-rl;
    text-orientation: mixed;
    color: rgba(255,255,255,0.8)
}

.box {
    background: rgba(0,0,0,0.6);
    clip-path: polygon(calc(100% - 30px) 0, 100% 30px, 100% calc(100% - 30px), calc(100% - 30px) 100%, 30px 100%, 0 calc(100% - 30px), 0 30px, 30px 0);
    border-left: 5px solid var(--main-cinza);
    height: 80%;
}

/****************************** Equipamentos *****/

.equipamentos {
    flex-basis: 32%;
}

.montador {
    height: 100%;;
}

.montador-conteudo {
    padding: 2em 10%;
}

.peca {
    padding: 1em 0;
}

.peca-titulo {
    color: var(--main-branco);
    text-transform: uppercase;
    font-size: 2.5em;
}

.controle {
    background: var(--main-preto);
    border-radius: 25px;
    float: right;
    display: inline-flex;
    padding: 5px;
    align-items: center;
    align-self: flex-end;
}

.controle-contador {
    width: 40px;
    height: 35px;
    background: none;
    border: 0;
    margin: 0 1rem;
    color: var(--main-branco);
    text-align: center;
    font-size: 2.5em;
    display: inline-flex;
    align-items: center;
    padding-top: 8px;
}

.controle-ajuste {
    display: inline-block;
    width: 40px;
    height: 40px;
    line-height: 44px;
    border-radius: 50%;
    color: var(--main-cinza);
    font-size: 4em;
    background: var(--main-preto);
    text-align: center;
    border: 3px solid var(--main-cinza);
    cursor: pointer;
}

.linha {
    border-color: var(--main-cinza);
}

.producao {
    margin-top: 1em;
    font-size: 2em;
    text-transform: uppercase;
    padding: 0.2em 1em;
    float: right;
    border: 3px solid var(--main-branco);
    background: var(--main-branco);
    clip-path: polygon(100% 0, 100% calc(100% - 30px), calc(100% - 30px) 100%, 0 100%, 0 0);
    cursor: pointer;
}

.producao:hover {
    background: var(--main-preto);
    color: var(--main-branco)
}



/****************************** Estatísticas *****/
.estatisticas {
    flex-basis: 23%;
    padding: 2em 2em 0;
}

.estatistica {
    color: var(--main-branco);
    display: flex;
    align-items: flex-start;
    height: 25%;
}

.estatistica-titulo {
    font-size: 1.5em;
    border-bottom: 1px solid var(--main-cinza);
    flex-basis: 40%;
    text-transform: uppercase;
    order: 1
}

.estatistica-valor {
    flex-basis: 60%;
    position: relative;
    margin: 10px 0 0;
    order: 2;
    margin: -10px 0 0;
}root {
    --main-cinza: #CCCCCC;
    --main-branco: #FFFFFF;
    --main-preto: #000000;
}

* {
    box-sizing: border-box;
}

body {
    background: url(../img/fundo.jpg);
    background-position: center center;
    background-size: cover cover;
    padding: 0;root {
    --main-cinza: #CCCCCC;
    --main-branco: #FFFFFF;
    --main-preto: #000000;
}

* {
    box-sizing: border-box;
}

body {
    background: url(../img/fundo.jpg);
    background-position: center center;
    background-size: cover cover;
    padding: 0;
    margin: 0;
    font-weight: 300;
}

body, input {
    font-family: 'Teko', sans-serif;
}

main {
    width: 80vw;
    height: 80vh;
    margin: 10vh 8vw 10vh 12vw;
    display: flex;
    gap: 1vw;
}

.robotron {
    background: url(../img/estrutura.png) no-repeat;
    background-position: center center;
    margin: 0;
    flex-basis: 40%;
    position: relative;
}

.robo {
    height: 110%;
    z-index: 1;
    position: absolute;
    left: -20%;
    top: -5%;
}

.titulo {
    transform: rotate(180deg);
    font-weight: 500;
    font-size: 130px;
    position: absolute;
    bottom: 7rem;
    left: -3rem;
    line-height: 0.8;
    writing-mode: vertical-rl;
    text-orientation: mixed;
    color: rgba(255,255,255,0.8)
}

.box {
    background: rgba(0,0,0,0.6);
    clip-path: polygon(calc(100% - 30px) 0, 100% 30px, 100% calc(100% - 30px), calc(100% - 30px) 100%, 30px 100%, 0 calc(100% - 30px), 0 30px, 30px 0);
    border-left: 5px solid var(--main-cinza);
    height: 80%;
}

/****************************** Equipamentos *****/

.equipamentos {
    flex-basis: 32%;
}

.montador {
    height: 100%;;
}

.montador-conteudo {
    padding: 2em 10%;
}

.peca {
    padding: 1em 0;
}

.peca-titulo {
    color: var(--main-branco);
    text-transform: uppercase;
    font-size: 2.5em;
}

.controle {
    background: var(--main-preto);
    border-radius: 25px;
    float: right;
    display: inline-flex;
    padding: 5px;
    align-items: center;
    align-self: flex-end;
}

.controle-contador {
    width: 40px;
    height: 35px;
    background: none;
    border: 0;
    margin: 0 1rem;
    color: var(--main-branco);
    text-align: center;
    font-size: 2.5em;
    display: inline-flex;
    align-items: center;
    padding-top: 8px;
}

.controle-ajuste {
    display: inline-block;
    width: 40px;
    height: 40px;
    line-height: 44px;
    border-radius: 50%;
    color: var(--main-cinza);
    font-size: 4em;
    background: var(--main-preto);
    text-align: center;
    border: 3px solid var(--main-cinza);
    cursor: pointer;
}

.linha {
    border-color: var(--main-cinza);
}

.producao {
    margin-top: 1em;
    font-size: 2em;
    text-transform: uppercase;
    padding: 0.2em 1em;
    float: right;
    border: 3px solid var(--main-branco);
    background: var(--main-branco);
    clip-path: polygon(100% 0, 100% calc(100% - 30px), calc(100% - 30px) 100%, 0 100%, 0 0);
    cursor: pointer;
}

.producao:hover {
    background: var(--main-preto);
    color: var(--main-branco)
}



/****************************** Estatísticas *****/
.estatisticas {
    flex-basis: 23%;
    padding: 2em 2em 0;
}

.estatistica {
    color: var(--main-branco);
    display: flex;
    align-items: flex-start;
    height: 25%;
}

.estatistica-titulo {
    font-size: 1.5em;
    border-bottom: 1px solid var(--main-cinza);
    flex-basis: 40%;
    text-transform: uppercase;
    order: 1
}

.estatistica-valor {
    flex-basis: 60%;
    position: relative;
    mar

.estatistica-valor::after {
    content: "";
    display: block;
    padding-bottom: 100%;
    border: 1px solid var(--main-cinza);
    border-radius: 50%;
}

.estatistica-numero {
    position: absolute;
    top: 50%;
    transform: translateY(-46%);
    width: 100%;
    line-height: 100%;
    text-align: center;
    font-size: 3em;
    margin: 0;
}

.estatistica:nth-child(2n) .estatistica-titulo {
    order: 2;
    text-align: right;
}

.estatistica:nth-child(2n) .estatistica-valor {
    order: 1;
    flex-basis: 35%;
    margin: 10px 0 0;
}

@media screen and (max-width: 1600px) {
    body { 
        font-size: 14px;
    }
    main {
        width: 90vw;
        height: 80vh;
        margin: 5vh auto;
    }
}

@media screen and (max-width: 1200px) {
    body { 
        font-size: 13px;
    }

    main {
        width: 96vw;
        height: 80vh;
        margin: 10vh auto;
    }
}
