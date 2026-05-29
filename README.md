* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
    background-color: #f4f7f6; /* Cor de fundo suave */
}

/* Cabeçalho */
header {
    background-color: #2e7d32; /* Verde Agro */
    color: white;
    padding: 20px 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header .logo {
    font-size: 24px;
    font-weight: bold;
}

header nav ul {
    display: flex;
    list-style: none;
}

header nav ul li {
    margin-left: 20px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 16px;
}

header nav ul li a:hover {
    text-decoration: underline;
}

/* Área Principal */
.hero {
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 100px 20px;
    background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://unsplash.com') no-repeat center center/cover;
    color: white;
    min-height: 80vh;
}

.hero-content {
    max-width: 800px;
}

.hero h1 {
    font-size: 50px;
    margin-bottom: 15px;
    color: #fff9c4; /* Amarelo campo */
}

.hero p {
    font-size: 20px;
    margin-bottom: 30px;
}

/* Botão */
.btn-primary {
    background-color: #fbc02d; /* Amarelo Agro de Destaque */
    color: #27382b;
    border: none;
    padding: 15px 40px;
    font-size: 18px;
    font-weight: bold;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.btn-primary:hover {
    background-color: #f57f17;
}

/* Seção Dinâmica */
#info-agrinho {
    margin-top: 40px;
    background-color: rgba(255, 255, 255, 0.95);
    color: #333;
    padding: 30px;
    border-radius: 8px;
    text-align: left;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
}

#info-agrinho h2 {
    color: #2e7d32;
    margin-bottom: 15px;
}

#info-agrinho ul {
    margin-top: 10px;
    padding-left: 20px;
}

/* Classe utilitária para esconder */
.hidden {
    display: none;
}
