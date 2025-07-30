# Gmz-site
<!DOCTYPE html><html lang="pt">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>GMZ - Multisserviços</title>
  <style>
    :root {
      --azul: #0d6efd;
      --preto: #111;
      --verde: #198754;
      --branco: #fff;
    }* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background: var(--preto);
  color: var(--branco);
  line-height: 1.6;
}

header {
  background: linear-gradient(90deg, var(--azul), var(--verde));
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: sticky;
  top: 0;
  z-index: 10;
}

header h1 {
  font-size: 1.5rem;
}

nav a {
  color: var(--branco);
  margin-left: 1rem;
  text-decoration: none;
  transition: color 0.3s;
}

nav a:hover {
  color: #ccc;
}

section {
  padding: 3rem 2rem;
  animation: fadeIn 1s ease-in;
}

@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}

.home {
  background: var(--azul);
  text-align: center;
}

.produtos {
  background: var(--preto);
}

.sobre {
  background: var(--verde);
}

.contato {
  background: #222;
}

.notificacoes {
  background: #333;
}

form {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  max-width: 500px;
  margin: auto;
}

input, textarea, button {
  padding: 0.8rem;
  border: none;
  border-radius: 5px;
}

input, textarea {
  background: #444;
  color: var(--branco);
}

button {
  background: var(--verde);
  color: var(--branco);
  cursor: pointer;
  transition: background 0.3s;
}

button:hover {
  background: var(--azul);
}

@media (max-width: 768px) {
  header {
    flex-direction: column;
    align-items: flex-start;
  }

  nav {
    margin-top: 0.5rem;
  }
}

  </style>
</head>
<body>
  <header>
    <h1>GMZ Serviços</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#produtos">Produtos/Serviços</a>
      <a href="#sobre">Sobre</a>
      <a href="#contato">Contato</a>
      <a href="#notificacoes">Notificações</a>
    </nav>
  </header>  <section id="home" class="home">
    <h2>Bem-vindo à GMZ</h2>
    <p>Especialistas em roupas, instalações residenciais, montagem de electrobombas, antenas parabólicas e pintura.</p>
  </section>  <section id="produtos" class="produtos">
    <h2>Produtos e Serviços</h2>
    <ul>
      <li>Vendas de roupas</li>
      <li>Instalações residenciais</li>
      <li>Montagem de electrobomba</li>
      <li>Montagem de antena parabólica</li>
      <li>Serviços de pintura</li>
    </ul>
  </section>  <section id="sobre" class="sobre">
    <h2>Sobre a GMZ</h2>
    <p>A GMZ é uma mini empresa que combina experiência e dedicação para oferecer soluções em várias áreas. Compromisso com a qualidade e satisfação dos nossos clientes.</p>
  </section>  <section id="contato" class="contato">
    <h2>Fale Conosco</h2>
    <form>
      <input type="text" placeholder="Seu nome" required>
      <input type="email" placeholder="Seu e-mail" required>
      <textarea rows="4" placeholder="Sua mensagem" required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>  <section id="notificacoes" class="notificacoes">
    <h2>Notificações</h2>
    <p>Fique atento às promoções e novidades da GMZ aqui.</p>
  </section>
</body>
</html>
