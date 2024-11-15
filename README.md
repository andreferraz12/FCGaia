!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clube de Basquetebol</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #003366; /* Ajuste para as cores do logotipo do clube */
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;<
            background-color: #0055a5; /* Ajuste para as cores do logotipo do clube */
        }
        nav a {
            color: #fff;
            padding: 15px;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #003366;
        }
        .content {
            padding: 20px;
        }
        .section {
            margin-bottom: 40px;
        }
        footer {
            background-color: #003366;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Clube de Basquetebol</h1>
    </header>
    
    <nav>
        <a href="#sobre">Sobre Nós</a>
        <a href="#equipas">Equipas</a>
        <a href="#login">Login</a>
        <a href="#noticias">Notícias</a>
    </nav>

    <div class="content">
        <section id="sobre" class="section">
            <h2>Sobre Nós</h2>
            <p>Somos um clube dedicado ao desenvolvimento do basquetebol, valorizando o espírito de equipa e contribuindo para a nossa comunidade.</p>
            <img src="link-da-foto.jpg" alt="Foto do Clube" width="100%">
        </section>
        
        <section id="equipas" class="section">
            <h2>Equipas</h2>
            <p>Conhece as nossas equipas dos diferentes escalões, desde os Babys aos Sub12. Cada jogador faz parte desta grande família e contribui para o nosso sucesso.</p>
            <div>
                <h3>Sub8</h3>
                <p>Lista de jogadores e curiosidades.</p>
                <h3>Sub12</h3>
                <p>Lista de jogadores e curiosidades.</p>
                <!-- Adicionar mais categorias conforme necessário -->
            </div>
        </section>
        
        <section id="login" class="section">
            <h2>Login</h2>
            <p>Área de acesso restrito aos membros do clube. Aqui podes ver calendários de treinos, documentos importantes, e informações privadas.</p>
            <button onclick="location.href='login.html'">Entrar</button>
        </section>

        <section id="noticias" class="section">
            <h2>Notícias</h2>
            <p>Fique por dentro dos últimos resultados e eventos do clube. Confira regularmente para estar sempre atualizado.</p>
        </section>
    </div>
    
    <footer>
        <p>&copy; 2024 Clube de Basquetebol. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
