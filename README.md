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