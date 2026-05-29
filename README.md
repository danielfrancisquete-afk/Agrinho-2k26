<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agrinho 2026</title>
    <style>
        :root {
            --verde-agro: #2d6a4f;
            --verde-claro: #52b788;
            --amarelo-sol: #ffb703;
            --fundo-folha: #f4f9f4;
            --texto-escuro: #1b4332;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--fundo-folha);
            color: var(--texto-escuro);
            line-height: 1.6;
        }

        header {
            background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)), url('https://unsplash.com') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }

        header h1 {
            font-size: 3.5rem;
            margin-bottom: 10px;
            color: var(--amarelo-sol);
            text-shadow: 2px 2px 4px rgba(0,0,0,0.6);
        }

        header p {
            font-size: 1.5rem;
            font-weight: 500;
            max-width: 800px;
            margin: 0 auto;
        }

        .container {
            max-width: 1000px;
            margin: 40px auto;
            padding: 20px;
            background: white;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            text-align: center;
        }

        .tema-destaque {
            background-color: #d8f3dc;
            padding: 25px;
            border-radius: 8px;
            border-left: 8px solid var(--verde-agro);
            margin-bottom: 30px;
        }

        .btn-saiba {
            background-color: var(--amarelo-sol);
            color: var(--texto-escuro);
            border: none;
            padding: 15px 30px;
            font-size: 1.2rem;
            font-weight: bold;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        .btn-saiba:hover {
            background-color: var(--verde-agro);
            color: white;
            transform: translateY(-3px);
        }

        .conteudo-oculto {
            display: none;
            margin-top: 30px;
            padding-top: 20px;
            border-top: 2px dashed var(--verde-claro);
            text-align: left;
        }

        .conteudo-oculto h2 {
            color: var(--verde-agro);
            margin-bottom: 15px;
        }

        .conteudo-oculto ul {
            margin-left: 20px;
        }

        footer {
            background-color: var(--verde-agro);
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 50px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Agrinho 2026</h1>
        <p>Agro forte, futuro sustentável: equilíbrio entre produção e meio ambiente</p>
    </header>

    <div class="container">
        <div class="tema-destaque">
            <h2>O Maior Programa de Responsabilidade Social</h2>
            <p>O Agrinho promove a educação ambiental, inovação e cidadania, unindo campo e cidade para um futuro consciente.</p>
        </div>

        <button class="btn-saiba" onclick="toggleInfo()">Saiba Mais</button>

        <div id="maisInformacoes" class="conteudo-oculto">
            <h2>Como Funciona o Programa?</h2>
            <p>O Agrinho utiliza a pedagogia da pesquisa para estimular alunos e professores a serem protagonistas na construção do conhecimento. Veja o que é abordado:</p>
            <br>
            <ul>
                <li><strong>Sustentabilidade:</strong> Compreensão do agronegócio aliado à preservação do meio ambiente.</li>
                <li><strong>Conexão Campo e Cidade:</strong> Integração e importância do setor agropecuário.</li>
                <li><strong>Inovação e Ética:</strong> Estímulo à tecnologia no campo e à cidadania na sociedade.</li>
                <li><strong>Premiações:</strong> Projetos e redações premiados com certificados e smartphones.</li>
            </ul>
        </div>
    </div>

    <footer>
        <p>Agrinho 2026 - Cultivando conhecimento, colhendo o futuro.</p>
    </footer>

    <script>
        function toggleInfo() {
            var infoDiv = document.getElementById("maisInformacoes");
            if (infoDiv.style.display === "none" || infoDiv.style.display === "") {
                infoDiv.style.display = "block";
            } else {
                infoDiv.style.display = "none";
            }
        }
    </script>
</body>
</html>
