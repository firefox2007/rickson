<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" type="image/jpg" href="img/favicon.ico"/>
    <title>Robotron 2000</title>

    <link rel="stylesheet" href="css/style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Teko:wght@300;500&display=swap" rel="stylesheet"> 
</head>
<body>
    <main>
        <section class="robotron">
            <img class="robo" src="img/robotron.png" alt="Robotron">
            <figcaption class="titulo">ROBOTRON <br>2000</figcaption>
        </section>

        <section class="box estatisticas">
            <div class="estatistica">
                <p class="estatistica-titulo">Força</p>
                <div class="estatistica-valor">
                    <p class="estatistica-numero">768</p>
                </div>
            </div>
            <div class="estatistica">
                <p class="estatistica-titulo">Poder</p>
                <div class="estatistica-valor">
                    <p class="estatistica-numero">630</p>
                </div>
            </div>
            <div class="estatistica">
                <p class="estatistica-titulo">Energia</p>
                <div class="estatistica-valor">
                    <p class="estatistica-numero">289</p>
                </div>
            </div>
            <div class="estatistica">
                <p class="estatistica-titulo">Velocidade</p>
                <div class="estatistica-valor">
                    <p class="estatistica-numero">597</p>
                </div>
            </div>
        </section>

        <section class="equipamentos">
            <form action="" class="montador">
                <div class="box montador-conteudo">
                    <div class="peca">
                        <label for="" class="peca-titulo">Braços</label>
                        <div class="controle">
                            <buttom class="controle-ajuste">-</buttom>
                            <input type="text" class="controle-contador" value="00">
                            <buttom class="controle-ajuste">+</buttom>
                        </div>
                    </div>
                    <hr class="linha">
                    <div class="peca">
                        <label for="" class="peca-titulo">Blindagem</label>
                        <div class="controle">
                            <buttom class="controle-ajuste">-</buttom>
                            <input type="text" class="controle-contador" value="00">
                            <buttom class="controle-ajuste">+</buttom>
                        </div>
                    </div>
                    <hr class="linha">
                    <div class="peca">
                        <label for="" class="peca-titulo">Núcleos</label>
                        <div class="controle">
                            <buttom class="controle-ajuste">-</buttom>
                            <input type="text" class="controle-contador" value="00">
                            <buttom class="controle-ajuste">+</buttom>
                        </div>
                    </div>
                    <hr class="linha">
                    <div class="peca">
                        <label for="" class="peca-titulo">Pernas</label>
                        <div class="controle">
                            <buttom class="controle-ajuste">-</buttom>
                            <input type="text" class="controle-contador" value="00">
                            <buttom class="controle-ajuste">+</buttom>
                        </div>
                    </div>
                    <hr class="linha">
                    <div class="peca">
                        <label for="" class="peca-titulo">Foguetes</label>
                        <div class="controle">
                            <buttom class="controle-ajuste">-</buttom>
                            <input type="text" class="controle-contador" value="00">
                            <buttom class="controle-ajuste">+</buttom>
                        </div>
                    </div>
                </div>
                <input type="submit" value="Iniciar produção" class="producao" id="producao">
            </form>
        </section>
    </main>
</body>
</html>
