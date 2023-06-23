# meu-repositorio.s

<!DOCTYPE html>
<html>
<head>
  <title>Expresso 89</title>
  <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
  <header>
    <h1>Expresso 89 color</h1>
    
    <nav>
      <ul>
        <li><a href="#">Página Inicial</a></li>
        <li><a href="#">Serviços</a></li>
        <li><a href="#">Carros em Reforma</a></li>
        <li><a href="#">Orçamento</a></li>
        <li><a href="#">Sobre Nós</a></li>
        <li><a href="#">Contato</a></li>
      </ul>
    </nav>
  </header>

  <section id="banner">
    <h2>Reforma de Carros Nacionais</h2>
    <p>Serviços especializados em reforma, manutenção e personalização de carros nacionais.</p>
  </section>

  <section id="servicos">
    <h2>Nossos Serviços</h2>
    <div class="servico">
      <img src="https://novonegocio.com.br/wp-content/uploads/2012/01/como_montar_uma_funilaria_e_pintura.jpg" alt="funilaria e pintura">
      <h3>Funilaria e Pintura</h3>
      <p>Reforma completa da lataria e pintura do seu carro.</p>
    </div>
    <div class="servico">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQfR0VtdZBaKDjNwQnJNc9xMZZngZkdeJUurg&usqp=CAU" alt="adulterio no motor">
      <h3>motor</h3>
      <p>Revisão, reparos e manutenção mecânica para garantir o bom funcionamento do seu veículo.</p>
    </div>
    <div class="servico">
      <img src="https://fotos.jornaldocarro.estadao.com.br/jornal-do-carro/imagens/noticia/leitor-2-670.jpg" alt="costumização">
      <h3>custumização</h3>
      <p>customização de carros com acessórios, adesivos, rodas e muito mais.</p>
    </div>
  </section>

  <section id="carros-em-reforma">
    <h2>Carros em Reforma</h2>
    <div class="passat">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS39TTaBcx7jR2JCIaC_Aakn5v1gL8S5LRHkQ&usqp=CAU" alt="passat"width="150" height="auto">
      <h3>passat</h3>
      <p>Em reforma para ganhar um novo visual e melhor desempenho.</p>
    </div>
    <div class="gol quadrado">
      <img src="https://img.olx.com.br/images/18/183363771881696.jpg" alt="gol quadrado"width="150" height="auto">
      <h3>Volkswagen Gol</h3>
      <p>Em reforma para receber uma pintura personalizada e novos acessórios.</p>
    </div>
  </section>

  <section id="orcamento">
    <h2>Solicite um Orçamento</h2>
    <form>
      <label for="nome">Nome:</label>
      <input type="text" id="nome" name="nome" required>
      <label for="email">E-mail:</label>
      <input type="email" id="email" name="email" required>
      

CSS
body {
  background-color: #F2F2F2;
  font-family: "Courier New", Courier, monospace;
  margin: 0;
  padding: 0;
}

h1, h2, h3, h4, h5, h6 {
  font-family: "Georgia", serif;
  color: #333333;
}

header {
  background-color: #333333;
  padding: 20px;
  color: #FFFFFF;
}

nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

nav ul li {
  display: inline-block;
  margin-right: 20px;
}

nav ul li a {
  text-decoration: none;
  color: #FFFFFF;
  font-size: 16px;
}

section {
  padding: 40px;
}

#banner {
  background-image: url("banner.jpg");
  background-size: cover;
  background-position: center;
  text-align: center;
  color: #FFFFFF;
}

#servicos {
  background-color: #FFFFFF;
  text-align: center;
}

.servico {
  display: inline-block;
  width: 30%;
  margin: 20px;
  padding: 20px;
  background-color: #EEEEEE;
  border-radius: 5px;
}

.servico img {
  width: 100%;
  height: auto;
  border-radius: 5px;
}

#carros-em-reforma {
  background-color: #F2F2F2;
  text-align: center;
}

.carro {
  display: inline-block;
  width: 45%;
  margin: 20px;
  padding: 20px;
  background-color: #FFFFFF;
  border-radius: 5px;
}

.carro img {
  width: 100%;
  height: auto;
  border-radius: 5px;
}

#orcamento {
  background-color: #FFFFFF;
  text-align: center;
  padding: 40px;
}

form {
  display: flex;
  flex-direction: column;
  align-items: center;
}

label {
  margin-bottom: 10px;
  font-size: 16px;
}

input[type="text"],
input[type="email"] {
  width: 300px;
  padding: 10px;
  border: 1px solid #CCCCCC;
  border-radius: 5px;
  font-size: 16px;
  margin-bottom: 20px;
}

input[type="submit"] {
  width: 150px;
  padding: 10px;
  background-color: #333333;
  color: #FFFFFF;
  border: none;
  border-radius: 5px;
  font-size: 16px;
  cursor: pointer;
}

footer {
  background-color: #333333;
  padding: 20px;
  color: #FFFFFF;
  text-align: center;
}

