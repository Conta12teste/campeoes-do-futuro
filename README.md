<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Campeões do Futuro</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #121212;
            color: #fff;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background-color: #8B0000;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 3em;
            text-transform: uppercase;
            font-weight: bold;
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 20px 0 0 0;
        }
        nav ul li {
            display: inline;
            margin: 0 20px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 1.2em;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #FFD700;
        }
        #hero {
            text-align: center;
            padding: 150px 20px;
            background: url('https://source.unsplash.com/1600x900/?jiu-jitsu,gym') no-repeat center center/cover;
            position: relative;
        }
        #hero h2 {
            font-size: 3.5em;
            text-transform: uppercase;
            text-shadow: 2px 2px 10px rgba(0,0,0,0.7);
            font-weight: bold;
        }
        .btn {
            display: inline-block;
            padding: 15px 40px;
            margin-top: 20px;
            background-color: #FFD700;
            color: #121212;
            font-weight: bold;
            border-radius: 5px;
            text-decoration: none;
            transition: 0.3s;
        }
        .btn:hover {
            background-color: #FFC107;
        }
        section {
            padding: 60px 20px;
            text-align: center;
            max-width: 900px;
            margin: auto;
        }
        footer {
            background-color: #8B0000;
            text-align: center;
            padding: 20px;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Campeões do Futuro</h1>
        <nav>
            <ul>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#treinos">Treinos</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="hero">
        <h2>Transforme-se com o Jiu-Jitsu</h2>
        <p>Disciplina, força e superação para todos os níveis.</p>
        <a href="#contato" class="btn">Inscreva-se agora</a>
    </section>
    
    <section id="sobre">
        <h2>Sobre Nós</h2>
        <p>Fundado em 2018 por Gesilvânio Lima, conhecido como Cigano, o projeto Campeões do Futuro tem como missão transformar vidas através do Jiu-Jitsu. Com academias localizadas nos bairros Nova Vitória e Gleba E, oferecemos treinamento de alto nível para atletas iniciantes e avançados.</p>
    </section>
    
    <section id="treinos">
        <h2>Treinos</h2>
        <p>Temos horários flexíveis e turmas para todas as idades. Venha conhecer nossos treinos e iniciar sua jornada no Jiu-Jitsu.</p>
    </section>
    
    <section id="contato">
        <h2>Fale Conosco</h2>
        <p>Quer saber mais? Entre em contato pelo Instagram ou WhatsApp.</p>
        <p><strong>Instagram:</strong> <a href="https://www.instagram.com/campeoes_fight" target="_blank">@campeoes_fight</a></p>
    </section>
    
    <footer>
        <p>&copy; 2025 Campeões do Futuro - Todos os direitos reservados</p>
    </footer>
</body>
</html>
