# Agrinho-2k26
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agrinho 2026</title>
    <style>
        :root {
            --verde-agro: #2e7d32;
            --verde-claro: #4caf50;
            --amarelo-agro: #fbc02d;
            --marrom-agro: #5d4037;
            --branco: #ffffff;
            --fundo: #f1f8e9;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--fundo);
            color: var(--marrom-agro);
        }

        header {
            background-color: var(--verde-agro);
            color: var(--branco);
            text-align: center;
            padding: 3rem 1rem;
            border-bottom: 5px solid var(--amarelo-agro);
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 0.5rem;
        }

        header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }

        .container {
            max-width: 900px;
            margin: 3rem auto;
            padding: 2rem;
            background: var(--branco);
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        h2 {
            color: var(--verde-agro);
            margin-bottom: 1.5rem;
        }

        p.descricao {
            font-size: 1.1rem;
            line-height: 1.6;
            margin-bottom: 2rem;
            color: #4e342e;
        }

        .btn-saiba {
            background-color: var(--amarelo-agro);
            color: var(--marrom-agro);
            border: none;
            padding: 1rem 2.5rem;
            font-size: 1.2rem;
            font-weight: bold;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
        }

        .btn-saiba:hover {
            background-color: #f57f17;
            color: var(--branco);
            transform: translateY(-3px);
        }

        #info-extra {
            display: none;
            margin-top: 2.5rem;
            padding-top: 2rem;
            border-top: 2px dashed var(--verde-claro);
            text-align: left;
        }

        #info-extra ul {
            list-style-type: none;
            padding-left: 0;
        }

        #info-extra li {
            background: #e8f5e9;
            margin: 10px 0;
            padding: 1rem;
            border-left: 5px solid var(--verde-agro);
            border-radius: 4px;
        }

        footer {
            text-align: center;
            padding: 2rem;
            background-color: var(--marrom-agro);
            color: var(--branco);
            margin-top: 3rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>🌱 Agrinho 2026 🌱</h1>
        <p>Agro forte, futuro sustentável: equilíbrio entre produção e meio ambiente</p>
    </header>

    <div class="container">
        <h2>Conectando o campo e a sala de aula</h2>
        <p class="descricao">
            O Agrinho é o maior programa de responsabilidade social do Sistema FAEP/SENAR-PR. 
            Ele busca promover a educação ambiental, a cidadania e a inovação tecnológica para milhares de estudantes.
        </p>

        <button class="btn-saiba" onclick="toggleInfo()">Saiba Mais</button>

        <div id="info-extra">
            <h3>Como o Agrinho funciona?</h3>
            <p style="margin-bottom: 1.5rem; color: #4e342e;">Descubra os pilares deste grande projeto educacional:</p>
            <ul>
                <li><strong>Projetos e Concursos:</strong> Mobiliza alunos e professores com categorias que vão de redação e desenho à agrorobótica.</li>
                <li><strong>Material Didático:</strong> Oferece conteúdos exclusivos e gratuitos adaptados para a Educação Infantil e Ensino Fundamental.</li>
                <li><strong>Sustentabilidade:</strong> Propõe reflexões essenciais sobre o agronegócio sustentável e a preservação do meio ambiente.</li>
                <li><strong>Reconhecimento:</strong> Professores e estudantes têm seus projetos inovadores reconhecidos e premiados anualmente.</li>
            </ul>
        </div>
    </div>

    <footer>
        <p>Agrinho 2026 - Transformando o amanhã através da educação.</p>
    </footer>

    <script>
        function toggleInfo() {
            var infoBox = document.getElementById("info-extra");
            if (infoBox.style.display === "none" || infoBox.style.display === "") {
                infoBox.style.display = "block";
            } else {
                infoBox.style.display = "none";
            }
        }
    </script>
</body>
</html>
