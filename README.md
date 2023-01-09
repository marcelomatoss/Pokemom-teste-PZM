# Pokemom-teste-PZM
Uma mini aplicação que gera pokémons da primeira geração aleatoriamente, permitindo visualizar os últimos pokémons que foram gerados e opcionalmente renomea-los.
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Busca Pokemon</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="container">
        <h1>Trabalhando com <strong>HTML</strong>, <strong>CSS</strong> e usando o <strong>JavaScript</strong> para
            fazer consultas online.</h1>
        <hr>
        <div class="imagem">
            <img src="img/pokemon-logo.png">
        </div>
        <form>
            <div class="group-form">
                <label>Nome ou Número do Pokémon:</label>
                <input type="text" id="name" placeholder="Exemplo: Pikachu ou 25" required>
            </div>
            <div class="group-form">
                <input type="submit" value="Pesquisar">
            </div>
        </form>
        <div id="imgPokemon">
        </div>
        <div id="content">...</div>
    </div>
    <script src="script.js"></script>
</body>

</html>
