# terceirao
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Comunidade de Filmes</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Cabeçalho do site -->
    <header>
        <div class="logo">
            <h1>Comunidade de Filmes</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#perfil">Perfil</a></li>
                <li><a href="#recomendacoes">Recomendações</a></li>
                <li><a href="#forum">Fórum</a></li>
                <li><a href="#enquetes">Enquetes</a></li>
            </ul>
        </nav>
    </header>

    <!-- Perfil do Usuário -->
    <section id="perfil" class="section">
        <h2>Perfil do Usuário</h2>
        <div class="perfil-container">
            <div class="perfil-info">
                <img src="https://via.placeholder.com/150" alt="Avatar" class="avatar">
                <h3>Nome do Usuário</h3>
                <p>Filmes Assistidos: 120</p>
                <p>Filmes Favoritos: 30</p>
            </div>
            <div class="acoes">
                <button>Editar Perfil</button>
                <button>Criar Lista de Filmes</button>
            </div>
        </div>
    </section>

    <!-- Recomendações de Filmes -->
    <section id="recomendacoes" class="section">
        <h2>Recomendações de Filmes</h2>
        <div class="recomendacao-container">
            <div class="recomendacao">
                <img src="https://via.placeholder.com/100x150" alt="Filme">
                <h3>O Poderoso Chefão</h3>
                <p>Gênero: Crime, Drama</p>
            </div>
            <div class="recomendacao">
                <img src="https://via.placeholder.com/100x150" alt="Filme">
                <h3>Matrix</h3>
                <p>Gênero: Ação, Ficção Científica</p>
            </div>
        </div>
    </section>

    <!-- Fórum de Discussões -->
    <section id="forum" class="section">
        <h2>Fórum de Discussões</h2>
        <div class="forum-container">
            <div class="topico">
                <h3>Discussão: O Final de *Inception* (A Origem)</h3>
                <p>O que você acha do final do filme? Você acha que ele ficou no sonho ou acordou?</p>
                <button>Participar da Discussão</button>
            </div>
            <div class="topico">
                <h3>Qual seu filme de terror favorito?</h3>
                <p>Quais são os filmes de terror que mais te marcaram?</p>
                <button>Participar da Discussão</button>
            </div>
        </div>
    </section>

    <!-- Enquetes -->
    <section id="enquetes" class="section">
        <h2>Enquetes</h2>
        <div class="enquete">
            <h3>Qual é o melhor filme de 2023?</h3>
            <button>Votar</button>
        </div>
        <div class="enquete">
            <h3>Você prefere finais felizes ou trágicos?</h3>
            <button>Votar</button>
        </div>
    </section>

    <!-- Rodapé -->
    <footer>
        <p>&copy; 2023 Comunidade de Filmes | Todos os direitos reservados</p>
    </footer>

</body>
</html>
