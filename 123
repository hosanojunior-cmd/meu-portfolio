<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meu Portfólio</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f5f7fa;
      color: #333;
    }

    header {
      background: #111;
      color: #fff;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      position: sticky;
      top: 0;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 1.5rem;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      transition: 0.3s;
    }

    nav a:hover {
      color: #00bcd4;
    }

    .hero {
      height: 80vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      background: linear-gradient(135deg, #00bcd4, #2196f3);
      color: #fff;
      padding: 2rem;
    }

    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }

    .hero p {
      max-width: 600px;
      margin-bottom: 1.5rem;
    }

    .btn {
      background: #fff;
      color: #2196f3;
      padding: 0.7rem 1.5rem;
      border-radius: 25px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    .btn:hover {
      background: #e3f2fd;
    }

    section {
      padding: 3rem 2rem;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      text-align: center;
      margin-bottom: 2rem;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
    }

    .card {
      background: #fff;
      border-radius: 12px;
      padding: 1.5rem;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card h3 {
      margin-bottom: 0.5rem;
    }

    .card p {
      margin-bottom: 1rem;
    }

    .card a {
      text-decoration: none;
      color: #2196f3;
      font-weight: bold;
    }

    footer {
      background: #111;
      color: #fff;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }

    @media (max-width: 600px) {
      .hero h1 {
        font-size: 2rem;
      }

      header {
        flex-direction: column;
        align-items: flex-start;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Meu Portfólio</h1>
    <nav>
      <ul>
        <li><a href="#sobre">Sobre</a></li>
        <li><a href="#projetos">Projetos</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h1>Olá, eu sou Desenvolvedor</h1>
    <p>Crio soluções digitais modernas, focadas em performance, design e experiência do usuário.</p>
    <a href="#projetos" class="btn">Ver Projetos</a>
  </section>

  <section id="sobre">
    <h2>Sobre mim</h2>
    <p>
      Sou estudante do curso de Tecnologia em Sistemas para Internet, uma área que exige constante atualização, dedicação e capacidade de adaptação às novas demandas do mercado digital. Mesmo estando em fase de formação acadêmica, já possuo experiência prática relevante, com projetos desenvolvidos e implantados para grandes clientes.</br>
      Essa vivência profissional antecipada demonstra não apenas domínio técnico, mas também comprometimento, responsabilidade e habilidade para transformar ideias em soluções reais. Ao longo da minha trajetória, venho buscando unir conhecimento teórico e prática de mercado, sempre focado em entregar resultados de qualidade e em constante evolução como profissional da área de tecnologia.

    </p>
  </section>

  <section id="projetos">
    <h2>Meus Projetos</h2>
    <div class="projects" id="project-list"></div>
  </section>

  <footer>
    <p>© 2026 - Meu Portfólio</p>
  </footer>

  <script>
    const projetos = [
      {
        titulo: "Sistema Web",
        descricao: "Aplicação web desenvolvida com foco em performance e usabilidade.",
        link: "#"
      },
      {
        titulo: "Landing Page",
        descricao: "Página moderna e responsiva para conversão de clientes.",
        link: "#"
      },
      {
        titulo: "Projeto JavaScript",
        descricao: "Projeto interativo utilizando JavaScript puro.",
        link: "#"
      }
    ];

    const container = document.getElementById("project-list");

    projetos.forEach(projeto => {
      const card = document.createElement("div");
      card.classList.add("card");

      card.innerHTML = `
        <h3>${projeto.titulo}</h3>
        <p>${projeto.descricao}</p>
        <a href="${projeto.link}" target="_blank">Ver projeto</a>
      `;

      container.appendChild(card);
    });
  </script>

</body>
</html>
