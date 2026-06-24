<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Painel 4 Janelas Otimizado</title>
    <style>
        /* Remove margens e define o fundo escuro */
        body { 
            margin: 0; 
            padding: 10px; 
            background: #121212; 
            height: 100vh; 
            box-sizing: border-box;
            overflow: hidden; /* Evita barras de rolagem na página principal */
        }

        /* Container que gerencia a grade 2x2 */
        .grid-container {
            display: grid;
            grid-template-columns: repeat(2, 1fr); /* 2 colunas de tamanhos iguais */
            grid-template-rows: repeat(2, 1fr);    /* 2 linhas de tamanhos iguais */
            gap: 10px;                             /* Espaçamento entre as janelas */
            width: 100%;
            height: 100%;
        }

        /* Estilo responsivo de cada janela iframe */
        .janela {
            width: 100%;
            height: 100%;
            border: 2px solid #333;
            border-radius: 8px;
            background: #fff;
            box-sizing: border-box;
            transition: border-color 0.3s;
        }

        /* Efeito visual ao passar o mouse na janela */
        .janela:hover {
            border-color: #0076ff;
        }

        /* Adaptação para telas de celulares (opcional) */
        @media (max-width: 768px) {
            .grid-container {
                grid-template-columns: 1fr; /* Vira 1 coluna só em telas muito pequenas */
                grid-template-rows: repeat(4, 1fr);
                overflow-y: auto;
            }
        }
    </style>
</head>
<body>

    <div class="grid-container">
        <!-- Substitua as URLs abaixo pelos sites que você deseja exibir -->
        <iframe class="janela" src="https://www.effectivecpmnetwork.com/w6czkvcg?key=7d06d8809910a06ad24d4f5d30bd5a5e" loading="lazy"></iframe>
        <iframe class="janela" src="https://www.effectivecpmnetwork.com/pg92j7gi?key=21bd7e023dda6fc752d4488d0c87033c" loading="lazy"></iframe>
        <iframe class="janela" src="https://www.effectivecpmnetwork.com/eudxqrdvas?key=40a46aeeaad89e33e0289dbe0dd2cc51" loading="lazy"></iframe>
        <iframe class="janela" src="https://omg10.com/4/11197116" loading="lazy"></iframe>
    </div>

</body>
</html>
