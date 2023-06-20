Flex
Descrição
Nessa aula vamos ver uma introdução de como posicionar elementos usando o CSS Flexbox

Flexbox
Nos permite posicionar os elementos dentro da caixa
Controle em uma dimensão (horizontal ou vertical)
Alinhamento, direcionamento, ordenar e tamanhos
div.parent {
	display: flex;
}
Flex-direction
Qual a direção do flex: horizontal ou vertical
row | column
Alinhamento
justify-content
align-items

HTML

<div class="container">
  <div class="box blue"></div>
  <div class="box red"></div>
  <div class="box green"></div>
</div>

CSS

.container {
    display: flex;
    justify-content: space-between;
}
.box {
  width: 50px;
  height: 50px;
  margin-bottom: 8px;
}

.blue {
  background-color: blue;
}

.red {
    background-color: red;
}

.green {
    background-color: green;
}
Discover - Todos os direitos reservados

Rocketseat 2023



Posicionando foguetes | Rocketseat