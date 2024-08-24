# ADS_<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }

        nav {
            background-color: #444;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            margin: 20px;
        }

        .main-content {
            flex: 3;
            background-color: #f4f4f4;
            padding: 20px;
            margin-right: 20px;
        }

        .sidebar {
            flex: 1;
            background-color: #ddd;
            padding: 20px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bem-vindo ao Meu Site</h1>
    </header>

    <nav>
        <a href="#home">Início</a>
        <a href="#about">Sobre</a>
        <a href="#services">Serviços</a>
        <a href="#contact">Contato</a>
    </nav>

    <div class="container">
        <div class="main-content">
            <h2>Conteúdo Principal</h2>
            <p>Aqui vai o conteúdo principal do seu site.</p>
        </div>

        <aside class="sidebar">
            <h2>Barra Lateral</h2>
            <p>Aqui pode ir o conteúdo da barra lateral, como links ou informações adicionais.</p>
        </aside>
    </div>

    <footer>
        <p>© 2024 Meu Site. Todos os direitos reservados.</p>
    </footer>
</body>
</html>

