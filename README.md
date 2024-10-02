<h2>Este repositório foi criado para ajudar programadores brasileiros a entender e aplicar o modelo de layout flexível do CSS, o Flexbox. Este projeto consiste em uma página estática desenvolvida com HTML e CSS, onde cada propriedade do Flexbox é explicada e demonstrada com exemplos práticos.</h2>

<h1>🎯 Objetivo</h1>
<h2>O objetivo deste projeto é auxiliar desenvolvedores de todos os níveis a entender o Flexbox de maneira clara e visual. A ideia é cobrir desde os conceitos básicos até os mais avançados, mostrando o impacto de cada propriedade do Flexbox diretamente no layout de uma página web.</h2>
<h1>📋 Descrição do Projeto</h1>
<h2>Este projeto é uma página estática que utiliza apenas HTML e CSS. A página está estruturada para mostrar cada propriedade do Flexbox, como flex-direction, justify-content, align-items, entre outras, com exemplos práticos que ilustram o efeito de cada valor possível.</h2>

<h1>Estrutura do Projeto</h1>
<h2>* index.html: A página principal que contém toda a estrutura HTML.
* style.css: O arquivo de estilos CSS que define o layout utilizando Flexbox.</h2>

<h1>Demonstrações Incluídas</h1>
<h2>A página é dividida em duas sessões, sendo demonstrando as propriedades aplicadas ao Flex Container e a segunda, ao Flex Item.</h2>

<h1>Explicação</h1>
<h2>Flexbox é uma framework de CSS que permite o programador posicionar os elementos da forma adaptativa e prática.</h2>  

<h2>O Flex Container é o elemento pai, a tag HTML que abriga os Flex itens ao lhe ser atribuido no CSS display:flex.</h2>

<h2>Os Flex Itens são os filhos diretos do Flex Container. Um flex-item pode ser um Flex Container também, basta ter elementos filhos e a propriedade display com o valor flex. Portanto, se uma tag é um elemento pai ou filho assim como se é um Flex Container ou um Flex iten depende do ponto de referência </h2>

<h2>* Cada seção contém uma descrição da propriedade, valores possíveis e um exemplo visual.
A página estática inclui demonstrações  das seguintes propriedades Flexbox:</h2>

<h2>Flex Container</h2>
  
* display: flex
```
.flex{
    display: flex;
}
```
* flex-direction
  ```
  .column {
	min-height: 200px;
	flex-direction: column;
}
```
* flex-whrap
```
.wrap {
	flex-wrap: wrap;
}

```
* flex-flow
```
.row-wrap {
	flex-flow: row wrap;
}
```
* justfy-content
```
.flex-center {
	justify-content: center;
}
```
* align-itens
```
.stretch {
	align-items: stretch;
}
```
* align-content
```
.align-space-around {
	align-content: space-around;
}
```

<h1>Flex Item</h1>
* flex-grow
```
.basis-grow {
	flex-grow: 1;
}
```
* flex-basis
```
.basis-auto {
	flex-basis: auto;
}
```
* flex-shrink
```
.shrink-1{
flex-shrink: 1;
}
```
* flex
```
.flexx {
	display: flex;
}
* order
```
}
.order1 {
	order: 1;
}
```
* align-self

```
```
.flex-end {
	align-self: flex-end;
}
```
