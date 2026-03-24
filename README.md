<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meu Perfil GitHub</title>

  <!-- Fonte bonita -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(-45deg, #0f2027, #203a43, #2c5364, #1c1c1c);
      background-size: 400% 400%;
      animation: gradientBG 10s ease infinite;
      color: white;
      text-align: center;
    }

    @keyframes gradientBG {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .container {
      padding: 40px;
    }

    img.avatar {
      width: 150px;
      border-radius: 50%;
      border: 4px solid #00ffc8;
      margin-bottom: 20px;
      animation: float 3s ease-in-out infinite;
    }

    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }

    h1 {
      font-size: 2.5em;
      margin: 10px 0;
    }

    .typing {
      border-right: 2px solid #00ffc8;
      white-space: nowrap;
      overflow: hidden;
      width: 0;
      margin: 0 auto;
      animation: typing 4s steps(40, end) forwards, blink 0.7s infinite;
    }

    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }

    @keyframes blink {
      50% { border-color: transparent }
    }

    p {
      font-size: 1.2em;
      opacity: 0.8;
    }

    .card {
      background: rgba(255, 255, 255, 0.1);
      border-radius: 20px;
      padding: 20px;
      margin: 20px auto;
      width: 80%;
      max-width: 600px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.4);
      transition: transform 0.3s;
    }

    .card:hover {
      transform: scale(1.05);
    }

    .badges img {
      margin: 5px;
    }

    .btn {
      display: inline-block;
      padding: 10px 20px;
      margin: 10px;
      border-radius: 25px;
      background: #00ffc8;
      color: black;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    .btn:hover {
      background: #00cfa3;
      transform: scale(1.1);
    }

    footer {
      margin-top: 30px;
      font-size: 0.9em;
      opacity: 0.6;
    }
  </style>
</head>
<body>

  <div class="container">
    <img class="avatar" src="https://avatars.githubusercontent.com/u/1?v=4" alt="avatar">
    <h1>👨‍💻 Thierry Bonato</h1>

    <p class="typing">Estudante de Ciência da Computação | Focado em evolução 🚀</p>

    <div class="card">
      <h2>🚀 Sobre mim</h2>
      <p>📚 Estudando C++, Java, HTML, CSS, MySQL, ...</p>
      <p>🎯 Objetivo: crescer na área de tecnologia</p>
    </div>

    <div class="card">
      <h2>⚡ Tecnologias</h2>
      <div class="badges">
        <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white">
        <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
        <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
      </div>
    </div>

    <div class="card">
      <h2>📊 Estatísticas</h2>
      <img src="https://github-readme-stats.vercel.app/api?username=THbonato&show_icons=true&theme=tokyonight">
      <br><br>
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=THbonato&layout=compact&theme=tokyonight">
    </div>

    <div class="card">
      <h2>🌐 Redes</h2>
      <a class="btn" href="https://github.com/THbonato" target="_blank">GitHub</a>
      <a class="btn" href="https://www.linkedin.com/in/thierry-bonato" target="_blank">LinkedIn</a>
    </div>

    <footer>
      Feito por Thierry
    </footer>
  </div>

</body>
</html>
