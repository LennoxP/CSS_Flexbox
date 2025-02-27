# 5\. Técnicas e Padrões de Layout com Flexbox

## 5.1 Criando um layout de coluna responsivo 
**Objetivo:** Organizar os elementos na vertical, como uma pilha.

### Passos:
1. Criamos um `div` com a classe `.column-layout`.
2. Usamos `display: flex;` e `flex-direction: column;` para alinhar os elementos verticalmente.
3. `align-items: center;` mantém os itens centralizados na horizontal.
4. `gap: 10px;` adiciona espaçamento entre os itens.

**Uso:** Bom para layouts de formulários ou listas verticais.

**Ex:**
![<gridExample>](<./img5/5.1-layout-de-coluna-responsivo.PNG>)  

## 5.2 Criando um layout de linha responsivo 
**Objetivo:** Posicionar um elemento no centro da tela.

### Passos:
1. Criamos um `div` com a classe `.center-layout`.
2. `display: flex;` ativa o Flexbox.
3. `justify-content: center;` centraliza horizontalmente.
4. `align-items: center;` centraliza verticalmente.
5. `height: 200px;` define uma altura para ver o efeito claramente.

**Uso:** Muito útil para botões de chamada para ação (CTAs) ou caixas de mensagens.

**Ex:**
![<gridExample>](<./img5/5.2-layout-de-linha-responsivo.PNG>)  

## 5.3 Centralizando elementos com Flexbox 
**Objetivo:** Posicionar um elemento no centro da tela.

### Passos:
1. Criamos um `div` com a classe `.center-layout`.
2. `display: flex;` ativa o Flexbox.
3. `justify-content: center;` centraliza horizontalmente.
4. `align-items: center;` centraliza verticalmente.
5. `height: 200px;` define uma altura para ver o efeito claramente.

**Uso:** Muito útil para botões de chamada para ação (CTAs) ou caixas de mensagens.

**Ex:**
![<gridExample>](<./img5/5.3-centralizacao-com-flexbox.PNG>)  

## 5.4 Criando um menu de navegação flexível 
**Objetivo:** Criar um menu de navegação com espaçamento uniforme.

### Passos:
1. Criamos um `nav` com a classe `.nav-menu`.
2. `display: flex;` coloca os links na mesma linha.
3. `justify-content: space-around;` distribui os links de forma uniforme.
4. `padding: 10px;` adiciona espaço interno.
5. `background: darkslategray;` dá cor ao menu.
6. Os links `<a>` possuem `color: white;` e `text-decoration: none;` para estilo.

**Uso:** Perfeito para menus responsivos e barras de navegação.

**Ex:**
![<gridExample>](<./img5/5.4-menu-de-navegacao-flexivel.PNG>)  

## 5.5 Criando um Grid de Cards com Flexbox
**Objetivo:** Criar uma grade de cartões organizados de maneira flexível.

### Passos:
1. Criamos um `div` com a classe `.card-grid`.
2. `display: flex;` organiza os cartões lado a lado.
3. `flex-wrap: wrap;` permite que os cartões se ajustem à tela.
4. `gap: 10px;` adiciona espaçamento entre os cartões.
5. Cada cartão `.card` tem `width: 200px;` e `text-align: center;` para melhor aparência.

**Uso:** Perfeito para catálogos de produtos ou listagens de conteúdos.

**Ex:**
![<gridExample>](<./img5/5.5-grid-de-cards-com-flexbox.PNG>)  
