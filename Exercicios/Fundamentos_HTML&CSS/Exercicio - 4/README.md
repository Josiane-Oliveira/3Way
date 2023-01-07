Exercícios de CSS
4. Ajuste o padding de um elemento

styles.css

.texto-injetado {
margin-bottom: -25px;
text-align: center;
}

.caixa {
border-style: solid;
border-color: black;
border-width: 5px;
text-align: center;
}

.caixa-amarela {
background-color: yellow;
padding: 10px;
}

.caixa-vermelha {
background-color: crimson;
color: #fff;
padding: 20px;
}

.caixa-azul {
background-color: blue;
color: #fff;
padding: 10px;
}

index.html

<h5 class="texto-injetado">margin</h5>
<div class="caixa caixa-amarela">
<h5 class="caixa caixa-vermelha">padding</h5>
<h5 class="caixa caixa-azul">padding</h5>
</div>