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
