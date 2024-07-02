- 👋 Hi, I’m @lospimenta
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
lospimenta/lospimenta is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lar Doce Aroma</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Lato:wght@300;400;700&display=swap">
</head>
<body>
    <header>
        <div class="logo">
            <img src="logo.png" alt="Lar Doce Aroma">
            <h1>Lar Doce Aroma</h1>
        </div>
        <p class="tagline">Transforme sua casa em um lar, fragrância por fragrância.</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#products">Produtos</a></li>
            <li><a href="#about">Sobre Nós</a></li>
            <li><a href="#contact">Contato</a></li>
        </ul>
    </nav>
    
    <main>
        <section id="home">
            <h2>Bem-vindo à Lar Doce Aroma</h2>
            <p>Descubra nossos aromas exclusivos que transformam qualquer espaço em um verdadeiro lar.</p>
        </section>
        
        <section id="products">
            <h2>Produtos</h2>
            <div class="product-list">
                <!-- Adicione seus produtos aqui -->
            </div>
        </section>
        
        <section id="about">
            <h2>Sobre Nós</h2>
            <p>Nossa missão é trazer conforto e bem-estar através de aromas únicos e de alta qualidade.</p>
        </section>
        
        <section id="contact">
            <h2>Contato</h2>
            <form action="#" method="post">
                <label for="name">Nome:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Mensagem:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">Enviar</button>
            </form>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2024 Lar Doce Aroma. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
body {
    font-family: 'Lato', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #F7EFE2;
    color: #333;
}

header {
    background-color: #E2725B;
    color: #FFF;
    text-align: center;
    padding: 20px;
}

header .logo {
    display: flex;
    align-items: center;
    justify-content: center;
}

header .logo img {
    height: 50px;
    margin-right: 10px;
}

header h1 {
    font-family: 'Great Vibes', cursive;
    font-size: 3em;
}

.tagline {
    font-family: 'Lato', sans-serif;
    font-size: 1.2em;
}

nav {
    background-color: #9BAF97;
    text-align: center;
    padding: 10px 0;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: #FFF;
    font-weight: 700;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 40px;
}

footer {
    background-color: #333;
    color: #FFF;
    text-align: center;
    padding: 10px;
}

