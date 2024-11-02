# aula-10-html-css-2024
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário</title>
</head>

<body>
    <h1>Formulário</h1>
    <form name="form1" method="post" action="http://hebertphp.awardspace.us/recebe.php">
        <label for="login">Login</label> <input type="text" id="login" name="login" placeholder="Digite seu login"
            required><b>*</b><br>
        <label for="senha">Senha</label> <input type="password" id="senha" name="senha" placeholder="Digite sua senha"
            required><b>*</b><br>
        Data <input type="datetime-local" id="data" name="data"><br>
        <input type="hidden" name="vai" value="ja foi">
        <h2>selecine uma ou mais linguagens</h2>
        <input type="checkbox" name="js" id="JS" checked> <label for="js">JS</label><br>
        <input type="checkbox" name="php" id="PHP"><label for="php">PHP</label> <br>
        <input type="checkbox" name="sgl" id="SGL"><label for="slg">SGL</label> <br>
        <h2>Qual o dia da semana da aula de HTML/CSS</h2>
        <input type="radio" name="semana" value="segunda" id="segunda" required><label for="segunda">Segunda</label><br>
        <input type="radio" name="semana" value="terça" id="terça"><label for="terça">Terça</label><br>
        <input type="radio" name="semana" value="quarta" id="quarta"><label for="quarta">Quarta</label><br>
        <input type="radio" name="semana" value="quinta" id="quinta><label for=" quinta">Quinta</label><br>
        <input type="radio" name="semana" value="sexta" id="sexta"><label for="sexta">Sexta</label><br>
        Selecione UF<select name="uf">
            <option value="RJ">Rio de janeiro</option>
            <option>MG</option>
            <option selected>SP </option>
            <option>ES</option>
        </select><br>
        Mensagem <textarea name="msg" rows="10" cols="40"
            placeholder="Digite sua mensagem">Digite sua Mensagem</textarea>
        <input type="submit" value="Enviar!"><input type="reset" value="Limpar Dados!">
    </form><br>
    <p><b>*</b> - Campo obrigaório</p>
</body>

</html>
