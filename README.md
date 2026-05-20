<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Blog</title>
        <style>
            header{
                background-color: rgb(66, 2, 2);
                color: #FFFFFF;
                text-align: center;
                max-width: 800px;
                margin: 0 auto;
                padding: 16px;
                border: 5px solid #cf1010;
            }
            main{
                background-color: #FFFFFF;
                color: rgb(66, 2, 2);
                max-width: 800px;
                margin: 0 auto;
                padding: 16px;
                display: flex;

            }
            img{
                width: 150px;
                height: 150px;
            }
            .artigo-ator{
                font-weight: bold;
            }
        </style>

    </head>
    <body>
        <header>
            <h1>Meu blog da Unidade 1</h1>
            <p>Vou postar informações do processo e resultado da Unidade Página web: do zero à primeira interação</p>
        </header>        
        <main>
            <img src="Imagem-blog2.png" alt="Logo minimalista para blog de séries de televisão com fundo vermelho escuro, ícone de televisão retrô em branco e texto “SÉRIE DE TELEVISÃO” em destaque com design moderno e elegante.">
            <div>

                <h2>Meu primeiro post</h2>
                <p class="artigo-autor"> Por: Prof Josi Guarda</p>
                <p>Boas-vindas ao meu novo Blog! Aqui vou compartilhar o passo a passo das aulas e os resutados dos projetos</p>
            <button>e.g., smile <span>0</span></button>
            </div>
        </main>
    </body>
    <script>
        const botao = querySelector("button");
        botao.addEventListener ("click, botaoClicado");

        function botaoClicado(){
            console.log("fui clicado");
            let texto = botao.querySelector("span");
            texto.textContent++;
        }

    </script>
</html>
