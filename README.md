<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Seu Nome - Site Pessoal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            text-align: center;
            margin: 1em 0;
        }
        nav a {
            text-decoration: none;
            color: #333;
            padding: 0.5em 1em;
            margin: 0 0.5em;
            border-radius: 5px;
            background-color: #ddd;
        }
        nav a:hover {
            background-color: #ccc;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px;
        }
        .main {
            width: 100%;
            background: #fff;
            padding: 20px;
            box-sizing: border-box;
            margin-bottom: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .main h2 {
            border-bottom: 2px solid #333;
            padding-bottom: 10px;
        }
        .main article {
            margin-bottom: 20px;
        }
        .main article h3 {
            margin-top: 0;
        }
        .main article p {
            margin-top: 0.5em;
            line-height: 1.4;
        }
        .sidebar {
            float: right;
            width: 30%;
            background: #f0f0f0;
            padding: 20px;
            box-sizing: border-box;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .sidebar h2 {
            margin-top: 0;
            border-bottom: 2px solid #333;
            padding-bottom: 10px;
        }
        .footer {
            clear: both;
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: #fff;
        }
    </style>
</head>
<body>

<header>
    <h1>Seu Nome - Site Pessoal</h1>
    <p>Publicações Esportivas e Interatividade com os Fãs</p>
</header>

<nav>
    <a href="#inicio">Início</a>
    <a href="#blog">Blog</a>
    <a href="#portfolio">Portfólio</a>
    <a href="#contato">Contato</a>
</nav>

<div class="container">

    <section id="inicio" class="main">
        <h2>Seja Bem-vindo ao Meu Site!</h2>
        <p>Olá, eu sou [Seu Nome]. Aqui você encontrará conteúdo emocionante sobre o mundo dos esportes, análises, notícias e muito mais. Vamos explorar juntos o que há de melhor no universo esportivo!</p>
    </section>

    <aside class="sidebar">
        <h2>Sobre Mim</h2>
        <p>Apresente-se brevemente aqui, fale sobre sua paixão por esportes e o que motivou a criar este site.</p>
    </aside>

    <section id="blog" class="main">
        <h2>Blog de Esportes</h2>
        <article>
            <h3>Título do Artigo 1</h3>
            <p>Resumo ou introdução do primeiro artigo.</p>
            <a href="#">Leia mais...</a>
        </article>
        <article>
            <h3>Título do Artigo 2</h3>
            <p>Resumo ou introdução do segundo artigo.</p>
            <a href="#">Leia mais...</a>
        </article>
        <!-- Adicione mais artigos conforme necessário -->
    </section>

    <aside class="sidebar">
        <h2>Redes Sociais</h2>
        <p>Conecte-se comigo nas redes sociais:</p>
        <ul>
            <li><a href="#">Twitter</a></li>
            <li><a href="#">Instagram</a></li>
            <li><a href="#">Facebook</a></li>
        </ul>
    </aside>

    <section id="portfolio" class="main">
        <h2>Meu Portfólio</h2>
        <p>Aqui você pode destacar projetos esportivos anteriores, colaborações ou qualquer outro trabalho relevante no campo esportivo.</p>
    </section>

    <aside class="sidebar">
        <h2>Anúncios e Parceiros</h2>
        <p>Espaço para anúncios ou informações sobre parceiros.</p>
    </aside>

    <section id="contato" class="main">
        <h2>Entre em Contato</h2>
        <p>Quer conversar sobre esportes? Fique à vontade para entrar em contato comigo:</p>
        <form>
            <label for="nome">Nome:</label><br>
            <input type="text" id="nome" name="nome"><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email"><br>
            <label for="mensagem">Mensagem:</label><br>
            <textarea id="mensagem" name="mensagem" rows="4"></textarea><br>
            <input type="submit" value="Enviar">
        </form>
    </section>

</div>

<footer class="footer">
    <p>&copy; 2024 Seu Nome. Todos os direitos reservados.</p>
</footer>

</body>
</html>
