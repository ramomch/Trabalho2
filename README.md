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