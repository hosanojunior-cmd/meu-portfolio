<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meu Portfólio</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
    }

    header {
      background: #333;
      color: #fff;
      padding: 1rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 1rem;
    }

    nav a {
      color: #fff;
      text-decoration: none;
    }

    section {
      padding: 2rem;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
    }

    .card {
      border: 1px solid #ccc;
      padding: 1rem;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 1rem;
    }

    @media (max-width: 600px) {
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

  <section id="sobre">
    <h2>Sobre mim</h2>
    <p>Sou estudante do curso de Tecnologia em Sistemas para Internet, uma área que exige constante atualização, dedicação e capacidade de adaptação às novas demandas do mercado digital. Mesmo estando em fase de formação acadêmica, já possuo experiência prática relevante, com projetos desenvolvidos e implantados para grandes clientes.</br>
      Essa vivência profissional antecipada demonstra não apenas domínio técnico, mas também comprometimento, responsabilidade e habilidade para transformar ideias em soluções reais. Ao longo da minha trajetória, venho buscando unir conhecimento teórico e prática de mercado, sempre focado em entregar resultados de qualidade e em constante evolução como profissional da área de tecnologia.</p>
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
        titulo: "Projeto 1",
        descricao: "Descrição do projeto 1",
        link: "#"
      },
      {
        titulo: "Projeto 2",
        descricao: "Descrição do projeto 2",
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
