# 3\. Propriedades do Contêiner Flexível

## 3.1 flex-direction **–** Direção dos elementos

 Define a direção principal em que os itens são organizados. Pode assumir os valores row (linha), column (coluna), row-reverse (linha reversa) e column-reverse (coluna reversa).

 ![<gridExample>](<./img3/3.1-flex-direction.PNG>)  

## 3.2 flex-wrap – Quebra de linha dos itens

 Controla se os itens devem permanecer na mesma linha ou se podem ser distribuídos em múltiplas linhas. Os valores possíveis são nowrap, wrap e wrap-reverse.

 ![<gridExample>](<./img3/3.2-flex-wrap.PNG>)  

## 3.3 flex-flow – Atalho para flex-direction e flex-wrap

 A propriedade flex-flow combina flex-direction e flex-wrap em uma única linha, facilitando a escrita do código.

 ![<gridExample>](<./img3/3.3-flex-flow.PNG>)  

## 3.4 justify-content – Alinhamento horizontal dos itens

 Define como os itens são distribuídos ao longo do eixo principal. Os valores incluem flex-start, flex-end, center, space-between, space-around e space-evenly.

 ![<gridExample>](<./img3/3.4-justify-content.PNG>)  

## 3.5 align-items – Alinhamento vertical dos itens 

Determina como os itens são alinhados ao longo do eixo perpendicular ao principal. Pode ser configurado como stretch, flex-start, flex-end, center ou baseline.

![<gridExample>](<./img3/3.5-align-items.PNG>)  
## 3.6 align-content – Alinhamento em múltiplas linhas 

afeta o alinhamento das linhas quando há múltiplas linhas dentro do contêiner flexível. Funciona apenas quando flex-wrap: wrap está ativo.

![<gridExample>](<./img3/3.6-align-content.PNG>)  