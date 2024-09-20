# Meu-site
Site
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja Online - Vendas de Eletrônicos, Roupas e Artigos de Luxo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
        }

        nav a:hover {
            background-color: #555;
        }

        .container {
            width: 80%;
            margin: 20px auto;
        }

        h1 {
            text-align: center;
        }

        .category {
            display: inline-block;
            width: 30%;
            margin: 1.5%;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
            text-align: center;
        }

        .category h2 {
            font-size: 24px;
        }

        .category img {
            max-width: 100%;
            height: auto;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer a {
            color: #ffcc00;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<header>
    <h1>Loja Online - Eletrônicos, Roupas e Artigos de Luxo</h1>
</header>

<nav>
    <a href="#eletronicos">Eletrônicos</a>
    <a href="#roupas">Roupas</a>
    <a href="#luxo">Artigos de Luxo</a>
    <a href="#contato">Contato</a>
</nav>

<div class="container">
    <h1>Categorias de Produtos</h1>

    <div class="category" id="eletronicos">
        <h2>Eletrônicos</h2>
        <img src="https://via.placeholder.com/300x200?text=Eletr%C3%B4nicos" alt="Eletrônicos">
        <p>Os melhores aparelhos eletrônicos do mercado.</p>
    </div>

    <div class="category" id="roupas">
        <h2>Roupas</h2>
        <img src="https://via.placeholder.com/300x200?text=Roupas" alt="Roupas">
        <p>Moda e estilo para todas as ocasiões.</p>
    </div>

    <div class="category" id="luxo">
        <h2>Artigos de Luxo</h2>
        <img src="https://via.placeholder.com/300x200?text=Artigos+de+Luxo" alt="Artigos de Luxo">
        <p>Produtos exclusivos para quem tem bom gosto.</p>
    </div>

    <!-- Espaço para adicionar novas categorias -->
    <div class="category" id="novos">
        <h2>Nova Categoria</h2>
        <img src="https://via.placeholder.com/300x200?text=Nova+Categoria" alt="Nova Categoria">
        <p>Adicione novas categorias conforme necessário.</p>
    </div>
</div>

<footer id="contato">
    <p>Entre em contato conosco pelo WhatsApp: 
        <a href="https://wa.me/SEU_NUMERO" target="_blank">Clique aqui para falar via WhatsApp</a>
    </p>
    <p>&copy; 2024 - Loja Online. Todos os direitos reservados.</p>
</footer>

</body>
</html>
