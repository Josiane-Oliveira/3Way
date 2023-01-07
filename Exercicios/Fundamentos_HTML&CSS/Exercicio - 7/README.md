Exercícios de CSS
7. Prática 2 de margin e padding

Este é um pouco mais bonito e um pouco mais próximo de algo que você pode ver
no mundo real. Você precisará alterar um pouco mais do que apenas a margem e o
preenchimento para que pareça exatamente correto.

style.css

body {
background: #eee;
font-family: sans-serif;
}
.card {
width: 400px;
background: #fff;
margin: 16px auto;
}
.title {
background: #e3f4ff;
}
.content {
background: #e3f4ff;
}
.button-container {
background: #e3f4ff;
}button {
background: white;
border: 1px solid #eee;
}

index.html

<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width,
initial-scale=1.0">
<title>Prática 2 de Margin e Padding</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<div class="card">
<h1 class="title">I'm a card</h1>
<div class="content">I have content inside me..lorem
ipsum blah blah blah. Here's some stuff you need to
read.</div>
<div class="button-container">and a <button>BIG
BUTTON</button></div>
</div>
</body>
</html>

Autoverificação

Use esta seção para verificar seu trabalho. Nesses projetos, seu objetivo não é
atingir 100% de perfeição de pixel, mas usar as ferramentas que você aprendeu para chegar relativamente perto da saída desejada.
● Há 8px entre a borda do cartão e seu conteúdo (as seções azuis).
Há uma lacuna de 8px entre cada uma das seções azuis dentro do cartão.
O título do cartão usa uma fonte de 16px.
Há 8px entre o texto do título e a borda da seção do título.
A seção de conteúdo tem espaço de 16px na parte superior e inferior e 8px
em ambos os lados.
● Tudo dentro da seção .button-container é centralizado e há preenchimento de
8px.
● O Big Button está centrado em sua própria linha.
● The Big Button has 24px space on the sides, and 8px on top and bottom.