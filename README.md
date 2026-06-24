<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Painel 10 Janelas Otimizado</title>
    <style>
        /* Remove margens e define o fundo escuro */
        body { 
            margin: 0; 
            padding: 10px; 
            background: #121212; 
            min-height: 100vh; /* Permite que a página cresça verticalmente */
            box-sizing: border-box;
            /* overflow: hidden; REMOVIDO para permitir a rolagem das 10 janelas */
        }

        /* Container que gerencia a grade de 2 colunas e 5 linhas */
        .grid-container {
            display: grid;
            grid-template-columns: repeat(2, 1fr); /* Mantém 2 colunas de tamanhos iguais */
            grid-template-rows: repeat(5, 450px);  /* Define 5 linhas com altura fixa para não esmagar os sites */
            gap: 10px;                             /* Espaçamento entre as janelas */
            width: 100%;
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

        /* Adaptação para telas de celulares */
        @media (max-width: 768px) {
            .grid-container {
                grid-template-columns: 1fr; /* Vira 1 coluna só em telas pequenas */
                grid-template-rows: repeat(10, 400px); /* 10 linhas em telas mobile */
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
        <iframe class="janela" src="https://www.effectivecpmnetwork.com/y8v4b1x4u?key=3908edbc4b34853d6b088301be76eedf" loading="lazy"></iframe>
        
        <!-- Novas janelas adicionadas para completar 10 -->
        <iframe class="janela" src="https://www.effectivecpmnetwork.com/d9qyggb6t?key=f0f7cac7f2aae79ff4591bf7f8773c87" loading="lazy"></iframe>
        <iframe class="janela" src="https://www.effectivecpmnetwork.com/d3dxwf48e?key=c88f1db71dd8060b4d63204d89aff104" loading="lazy"></iframe>
        <iframe class="janela" src="https://www.effectivecpmnetwork.com/rer8z03h?key=ff534dea47c1dab4058e75b5a0d0dee9" loading="lazy"></iframe>
        <iframe class="janela" src="https://www.effectivecpmnetwork.com/cmjznctw90?key=d24317add6eb687c85e6a4eb61cc7874" loading="lazy"></iframe>
        <iframe class="janela" src="https://www.effectivecpmnetwork.com/phb1zr8y?key=0d9c619ebfbd1d480811f174a7aa5882" loading="lazy"></iframe>
        <iframe class="janela" src="https://www.effectivecpmnetwork.com/em5eytsp?key=aa3c91efb241e4be1926d42084b02128" loading="lazy"></iframe>
    </div>

</body>
</html>

