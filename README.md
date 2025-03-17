<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Primeira Página</title>
</head>
<body>
    <h1>Oi, eu sou a Ramon!</h1>
    <h2>E esta é a minha primeira página HTML.</h2>
    <p>
        Criei essa página para praticar um pouquinho de HTML. 
        Ainda estou aprendendo, mas até que é legal 
       
    </p>

    <hr> <!-- Uma linha para dar aquela separada básica -->

    <h2>Um pouco sobre mim:</h2>
    <p>
        Bom, eu dias tranquilos, bons vinhos e cinema e musica.
    </p>
</body>
</html>

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página de Contato</title>
</head>
<body>
    <h1>Formulário de Contato</h1>
    <form action="#" method="post">
        <label for="nome">Nome:</label><br>
        <input type="text" id="nome" name="nome" required><br><br>

        <label for="email">E-mail:</label><br>
        <input type="email" id="email" name="email" required><br><br>

        <label for="mensagem">Mensagem:</label><br>
        <textarea id="mensagem" name="mensagem" rows="5" cols="40" required></textarea><br><br>

        <button type="submit">Enviar</button>
    </form>
</body>
</html>


<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Listas em HTML</title>
</head>
<body>
    <h1>Minhas Listas</h1>

    <!-- Lista Ordenada (Filmes/Séries Favoritos) -->
    <h2>Meus Filmes/Séries Favoritos</h2>
    <ol>
        <li>Antes do Amanheçer</li>
        <li>O amigo da minha amiga</li>
        <li>2046 </li>
    </ol>

    <!-- Lista Não Ordenada (Ingredientes para Café da Manhã) -->
    <h2>Ingredientes para um Café da Manhã Básico</h2>
    <ul>
        <li>Pão</li>
        <li>Manteiga</li>
        <li>Iogurte</li>
        <li>Pão de queijo</li>
        <li>Achocolatado</li>
    </ul>
</body>
</html>

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página com Links</title>
</head>
<body>
    <h1>Bem-vindo à Minha Página com Links</h1>

    <!-- Link para um site de livre escolha -->
    <p>Visite o site da <a href="https://filmesclassicos.com/index.htm" target="_blank">filmesclassicos</a>

    <!-- Link que abre em uma nova aba para um vídeo no YouTube -->
    <p>Assista a este vídeo interessante no YouTube: <a href="https://youtu.be/PvB0kWs2IPQ?si=zvMkqyRXRkfdmwKq"
</html>

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página com Imagens</title>
</head>
<body>
    <h1>Página com Imagens</h1>

    <!-- Primeira imagem: carregada a partir de um link externo -->
    <p>Imagem 1 - Carregada de um link externo:</p>
    <img src="https://via.placeholder.com/300x200" alt="Imagem externa de exemplo">

    <!-- Segunda imagem: carregada da mesma pasta do arquivo HTML -->
    <p>Imagem 2 - Carregada da mesma pasta do arquivo HTML:</p>
    <img src="imagem_local.jpg" alt="Imagem local">

    <!-- Terceira imagem: com texto alternativo descritivo -->
    <p>Imagem 3 - Com texto alternativo descritivo:</p>
    <img src="https://via.placeholder.com/300x200" alt="Imagem de exemplo com texto alternativo">
</body>
</html>

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabela de Produtos</title>
</head>
<body>

<h2>Tabela de Produtos Fictícios</h2>

<table border="1">
    <tr>
        <th>Produto</th>
        <th>Preço</th>
        <th>Descrição</th>
    </tr>
    <tr>
        <td>Ar condicionado dual inverter</td>
        <td>R$ 1.200,00</td>
        <td>Produto ideal para quem busca conforto e qualidade.</td>
    </tr>
    <tr>
        <td>Geladeira smart</td>
        <td>R$ 1.800,00</td>
        <td>Produto com tecnologia avançada para facilitar o seu dia a dia.</td>
    </tr>
    <tr>
        <td>Liquidificador e triturador</td>
        <td>R$ 495,00</td>
        <td>Produto durável e resistente, com design inovador.</td>
    </tr>
</table>

</body>
</html>

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currículo - João Silva da Luz</title>
</head>
<body>

    
    <header>
        <h1>João da Silva</h1>
        <h2>Desenvolvedor Web Full Stack</h2>
        <p>Email: joao.silva@example.com</p>
        <p>Telefone: (11) 98765-4321</p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/joaosilva">linkedin.com/in/joaosilva</a></p>
    </header>

    
    <section>
        <h2>Resumo Profissional</h2>
        <p>Desenvolvedor web com 5 anos de experiência em projetos de grande escala, especializado em tecnologias front-end e back-end. Habilidade em trabalhar em equipes ágeis e entregar soluções de alta qualidade dentro do prazo.</p>
    </section>

    
    <section>
        <h2>Experiência Profissional</h2>
        <article>
            <h3>Desenvolvedor Full Stack - Empresa XYZ</h3>
            <p><strong>Período:</strong> Janeiro 2020 - Presente</p>
            <p><strong>Descrição:</strong> Desenvolvimento e manutenção de aplicações web utilizando React, Node.js e MongoDB. Colaboração com equipes de design e produto para criar interfaces de usuário intuitivas.</p>
        </article>
        <article>
            <h3>Desenvolvedor Front-end - Empresa ABC</h3>
            <p><strong>Período:</strong> Junho 2017 - Dezembro 2019</p>
            <p><strong>Descrição:</strong> Implementação de designs responsivos e otimização de performance para aplicações web. Uso de HTML5, CSS3 e JavaScript para criar experiências de usuário fluidas.</p>
        </article>
    </section>

    
    <section>
        <h2>Formação Acadêmica</h2>
        <article>
            <h3>Bacharelado em Ciência da Computação</h3>
            <p><strong>Instituição:</strong> Universidade Federal de São Paulo (UNIFESP)</p>
            <p><strong>Período:</strong> 2013 - 2017</p>
        </article>
    </section>

    
    <section>
        <h2>Habilidades</h2>
        <ul>
            <li>HTML5, CSS3, JavaScript</li>
            <li>React, Angular, Vue.js</li>
            <li>Node.js, Express, MongoDB</li>
            <li>Git, Docker, CI/CD</li>
            <li>Metodologias Ágeis (Scrum, Kanban)</li>
        </ul>
    </section>

    
    <section>
        <h2>Idiomas</h2>
        <ul>
            <li>Português - Nativo</li>
            <li>Inglês - Avançado</li>
            <li>Espanhol - Intermediário</li>
        </ul>
    </section>

</body>
</html>

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Explora Mundo - Site de Viagens</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Cabeçalho -->
    <header>
        <h1>Explora Mundo</h1>
        <p>Descubra os melhores destinos para sua próxima aventura!</p>
    </header>

    <!-- Seção Principal -->
    <section class="destaque">
        <img src="https://via.placeholder.com/1200x400" alt="Imagem de destaque de viagem">
        <div class="texto-promocional">
            <h2>Viaje pelo mundo com conforto e segurança!</h2>
            <p>Encontre pacotes exclusivos e viva experiências inesquecíveis.</p>
            <a href="#" class="botao">Reserve Agora</a>
        </div>
    </section>

    <!-- Galeria de Destinos -->
    <section class="galeria">
        <h2>Destinos Populares</h2>
        <div class="destinos">
            <div class="destino">
                <img src="https://via.placeholder.com/300x200" alt="Paris">
                <h3>Paris, França</h3>
                <p>Conheça a Cidade Luz e seus pontos turísticos incríveis.</p>
            </div>
            <div class="destino">
                <img src="https://via.placeholder.com/300x200" alt="Tóquio">
                <h3>Tóquio, Japão</h3>
                <p>Explore a mistura de tradição e modernidade.</p>
            </div>
            <div class="destino">
                <img src="https://via.placeholder.com/300x200" alt="Nova York">
                <h3>Nova York, EUA</h3>
                <p>Descubra a cidade que nunca dorme.</p>
            </div>
        </div>
    </section>

    <!-- Rodapé -->
    <footer>
        <p>Entre em contato conosco:</p>
        <p>Email: contato@exploramundo.com | Telefone: (11) 1234-5678</p>
        <p>Siga-nos nas redes sociais:</p>
        <a href="#">Facebook</a> | 
        <a href="#">Instagram</a> | 
        <a href="#">Twitter</a>
    </footer>
</body>
</html>

/* Reset básico */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f4;
}

/* Cabeçalho */
header {
    background-color: #2c3e50;
    color: #fff;
    padding: 20px;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

/* Seção de Destaque */
.destaque {
    position: relative;
    text-align: center;
    margin-bottom: 30px;
}

.destaque img {
    width: 100%;
    height: auto;
}

.texto-promocional {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: rgba(0, 0, 0, 0.6);
    padding: 20px;
    color: #fff;
    border-radius: 10px;
}

.texto-promocional h2 {
    font-size: 2rem;
    margin-bottom: 10px;
}

.botao {
    display: inline-block;
    padding: 10px 20px;
    background-color: #e67e22;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s;
}

.botao:hover {
    background-color: #d35400;
}

/* Galeria de Destinos */
.galeria {
    padding: 20px;
    text-align: center;
}

.galeria h2 {
    font-size: 2rem;
    margin-bottom: 20px;
}

.destinos {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.destino {
    background-color: #fff;
    margin: 10px;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    width: 30%;
    transition: transform 0.3s;
}

.destino:hover {
    transform: scale(1.05);
}

.destino img {
    width: 100%;
    border-radius: 10px;
}

.destino h3 {
    font-size: 1.5rem;
    margin: 10px 0;
}

.destino p {
    font-size: 1rem;
    color: #666;
}

/* Rodapé */
footer {
    background-color: #2c3e50;
    color: #fff;
    text-align: center;
    padding: 20px;
    margin-top: 30px;
}

footer a {
    color: #e67e22;
    text-decoration: none;
    margin: 0 10px;
}

footer a:hover {
    text-decoration: underline;
}

/* Responsividade */
@media (max-width: 768px) {
    .destinos {
        flex-direction: column;
    }

    .destino {
        width: 100%;
    }

    .texto-promocional h2 {
        font-size: 1.5rem;
    }

    .texto-promocional p {
        font-size: 0.9rem;
    }
}
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galeria de Imagens</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Galeria de Imagens</h1>
    <img src="img/imagem1.jpg" alt="Batman e Robin">
    <img src="img/imagem2.jpg" alt="Curtindo um som">
    <img src="img/imagem3.jpg" alt="Pastel de queijo">
    <div class="banner"></div>
    <div class="galeria">
    <img src="img/imagem1.jpg" alt="Cachorro feliz">
    <img src="img/imagem2.jpg" alt="Paisagem montanhosa">
    <img src="img/imagem3.jpg" alt="Café e livro">
    <img src="img/imagem4.jpg" alt="Gato dormindo">
    <img src="img/imagem5.jpg" alt="Praia ao entardecer">
    <img src="img/imagem6.jpg" alt="Cidade iluminada">
</div>
</body>
</html>
img {
    max-width: 500px;
    height: auto;
}
.banner {
    width: 800px;
    height: 300px;
    background-image: url('img/banner.jpg');
    background-size: cover;
    background-position: center;
}
img {
    max-width: 500px;
    height: auto;
    transition: 0.3s ease-in-out;
}

img:hover {
    transform: scale(1.1);
}
.galeria {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
}

.galeria img {
    width: 100%;
    height: auto;
}

@media (max-width: 600px) {
    .galeria {

        img {
    max-width: 500px;
    height: auto;
}
.banner {
    width: 800px;
    height: 300px;
    background-image: url('img/banner.jpg');
    background-size: cover;
    background-position: center;
}
img {
    max-width: 500px;
    height: auto;
    transition: 0.3s ease-in-out;
}

img:hover {
    transform: scale(1.1);
}
.galeria {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
}

.galeria img {
    width: 100%;
    height: auto;
}

@media (max-width: 600px) {
    .galeria {
        grid-template-columns: repeat(2, 1fr);
    }
}

// Exercício 1: Declarando Variáveis
let nome = "Seu Nome"; // Substitua "Seu Nome" pelo seu nome real
console.log("Exercício 1:");
console.log(nome); // Exibe o valor da variável nome

// Exercício 2: Alterando o Valor da Variável
let idade = 25; // Valor inicial
console.log("\nExercício 2:");
console.log("Idade inicial:", idade); // Exibe o valor inicial
idade = 30; // Alterando o valor
console.log("Nova idade:", idade); // Exibe o novo valor

// Exercício 3: Usando const
const pi = 3.14;
console.log("\nExercício 3:");
console.log("Valor de pi:", pi); // Exibe o valor de pi
// pi = 3.1415; // Descomente esta linha para ver o erro (não é possível reatribuir const)

// Questão 4: Operador de Subtração
let a = 15;
let b = 5;
let diferenca = a - b;
console.log("\nQuestão 4:");
console.log("Diferença entre a e b:", diferenca); // Exibe o resultado da subtração

// Exercício 5: Variáveis e Escopo
console.log("\nExercício 5:");
function exemploEscopo() {
    let x = 10;
    console.log("Dentro da função, x =", x); // Funciona, pois x está no escopo da função
}
exemploEscopo();
// console.log(x); // Descomente esta linha para ver o erro (x não está definido fora da função)