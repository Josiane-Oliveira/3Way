Exercícios de CSS
6. Prática 1 de margin e padding

Para este primeiro exercício, simplesmente edite o arquivo style.css para que as divs
se pareçam com a imagem abaixo. Edite o CSS apenas onde instruído no arquivo.
Você só deve alterar os valores da margem e do preenchimento para este exercício.
Você não deve adicionar ou remover propriedades no CSS ou tocar no HTML.

style.css

body {
max-width: 600px;
margin: 0 auto;
}
.one {
background: pink;
border: 3px solid blue;
/* ALTERE-ME */padding: 0px;
margin: 0px;
}
.two {
background: lightblue;
border: 3px solid purple;
/* ALTERE-ME */
margin-bottom: 0px;
}
.three {
background: peachpuff;
border: 3px solid brown;
width: 200px;
/* ALTERE-ME */
padding: 0px;
margin-left: 0px;
}

index.html

<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width,
initial-scale=1.0">
<title>Exercícios de Margin e Padding</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<div class="one">
DIV ONE
</div>
<div class="two">
DIV TWO
</div>
<div class="three">
DIV THREE
</div>
</body>
</html>

Autoverificação
Use esta seção para verificar seu trabalho. Nesses projetos, seu objetivo não é
atingir 100% de perfeição de pixel, mas usar as ferramentas que você aprendeu para
chegar relativamente perto da saída desejada.
● Div One e Div Three têm 32px entre o texto e a borda.
● Div One tem 12px entre ele e qualquer outro elemento na página.
● Há uma lacuna de 48px entre a Div Two e a Div Three.
● A Div Three está alinhada à direita.
● O alinhamento da Div Three é obtido usando margin (e não float, flexbox,
etc.).