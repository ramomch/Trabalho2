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
