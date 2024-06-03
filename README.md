# Censo-espiritual
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Censo Espiritual da Igreja</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Censo Espiritual da Igreja</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Início</a></li>
            <li><a href="#form">Formulário</a></li>
            <li><a href="#contact">Contato</a></li>
        </ul>
    </nav>
    <main>
        <section id="home">
            <h2>Bem-vindo ao Censo Espiritual</h2>
            <p>Este censo nos ajudará a entender melhor as necessidades espirituais da nossa comunidade.</p>
        </section>
        <section id="form">
            <h2>Formulário de Censo</h2>
            <form id="censusForm">
                <label for="name">Nome:</label>
                <input type="text" id="name" name="name" required>

                <label for="age">Idade:</label>
                <input type="number" id="age" name="age" required>

                <label for="faith">Nível de Fé (1 a 10):</label>
                <input type="number" id="faith" name="faith" min="1" max="10" required>

                <label for="comments">Comentários:</label>
                <textarea id="comments" name="comments"></textarea>

                <button type="submit">Enviar</button>
            </form>
        </section>
        <section id="contact">
            <h2>Contato</h2>
            <p>Para mais informações, entre em contato conosco pelo email: contato@igreja.com</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Igreja. Todos os direitos reservados.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
