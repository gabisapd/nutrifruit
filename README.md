# nutrifruit
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NutriFruit - Saudável e Saboroso</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>
    <!-- Header -->
    <header class="header">
        <div class="logo">
            <img src="logo.png" alt="NutriFruit Logo">
            <h1>NutriFruit</h1>
        </div>
        <nav class="navigation">
            <ul>
                <li><a href="#inicio">Início</a></li>
                <li><a href="#receitas">Receitas Saudáveis</a></li>
                <li><a href="#beneficios">Benefícios Nutricionais</a></li>
                <li><a href="#loja">Loja Virtual</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="inicio">
        <img src="banner.jpg" alt="Frutas Nutritivas">
        <div class="hero-text">
            <h2>Transforme seu lanche com frutas nutritivas e cheias de sabor! 🌱🍍</h2>
            <button class="btn">Explore Nossas Delícias</button>
        </div>
    </section>

    <!-- Seção 1: Receitas em Destaque -->
    <section class="receitas" id="receitas">
        <h2>Receitas em Destaque 🥭🍌</h2>
        <div class="cards">
            <div class="card">
                <img src="manga-gengibre.jpg" alt="Rolinho de Manga com Gengibre">
                <h3>Rolinho de Manga com Gengibre</h3>
                <p>Leve e refrescante com um toque de saúde anti-inflamatória!</p>
                <button>Veja a Receita</button>
            </div>
            <div class="card">
                <img src="banana-canela.jpg" alt="Rolinho de Banana com Canela e Cacau">
                <h3>Rolinho de Banana com Canela e Cacau</h3>
                <p>Energia natural com um sabor irresistível de cacau!</p>
                <button>Veja a Receita</button>
            </div>
            <!-- Continue com os outros cards -->
        </div>
    </section>

    <!-- Seção 2: Benefícios dos Ingredientes -->
    <section class="beneficios" id="beneficios">
        <h2>Benefícios dos Ingredientes 🌱</h2>
        <div class="infografico">
            <div class="item" data-info="Rica em vitamina C e antioxidantes">
                <img src="manga-icon.png" alt="Manga">
                <p>Manga</p>
            </div>
            <div class="item" data-info="Propriedades anti-inflamatórias e termogênicas">
                <img src="gengibre-icon.png" alt="Gengibre">
                <p>Gengibre</p>
            </div>
            <!-- Continue com os outros ingredientes -->
        </div>
    </section>

    <!-- Seção 3: Loja Virtual -->
    <section class="loja" id="loja">
        <h2>Loja Virtual 🛒</h2>
        <div class="produtos">
            <div class="produto">
                <img src="rolinho-manga.jpg" alt="Rolinho de Manga">
                <h3>Rolinho de Manga com Gengibre</h3>
                <p>R$ 19,90 / 12 unidades</p>
                <button>Adicionar ao Carrinho</button>
            </div>
            <div class="produto">
                <img src="banana-canela.jpg" alt="Rolinho de Banana">
                <h3>Rolinho de Banana com Canela e Cacau</h3>
                <p>R$ 21,90 / 10 unidades</p>
                <button>Adicionar ao Carrinho</button>
            </div>
            <!-- Continue com os outros produtos -->
        </div>
    </section>

    <!-- Seção 4: Tabelas Nutricionais -->
    <section class="tabelas">
        <h2>Tabelas Nutricionais 📊</h2>
        <button class="btn">Veja as Informações Nutricionais</button>
    </section>

    <!-- Seção 5: Depoimentos -->
    <section class="depoimentos">
        <h2>Depoimentos e Avaliações ⭐</h2>
        <div class="carrossel">
            <blockquote>
                “As balinhas de manga com maracujá são deliciosas e me ajudaram muito a controlar o estresse!”
                <cite>— Carla M.</cite>
            </blockquote>
            <blockquote>
                “Os rolinhos de banana são meu lanche pós-treino favorito!”
                <cite>— Lucas R.</cite>
            </blockquote>
            <!-- Continue com outros depoimentos -->
        </div>
    </section>

    <!-- Seção 6: Newsletter -->
    <section class="newsletter">
        <h2>Receba Nossas Novidades 📬</h2>
        <form>
            <input type="email" placeholder="Digite seu e-mail" required>
            <button type="submit">Quero Me Inscrever!</button>
        </form>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="social">
            <a href="#">Instagram</a>
            <a href="#">Facebook</a>
            <a href="#">TikTok</a>
        </div>
        <p>Contato: contato@nutrifruit.com | (11) 1234-5678</p>
        <p>Copyright © 2024 NutriFruit</p>
    </footer>
</body>
</html>
