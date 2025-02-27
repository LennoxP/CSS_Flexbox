9. Conclusão e Melhores Práticas# 1\. Introdução ao CSS Flexbox

## Índice: CSS Flexbox para Alunos do Ensino Médio Técnico em Informática

## 1.1 O que é Flexbox?

Flexbox foi criado para tornar as tarefas de posicionamento algo mais fácil e compatível com os browsers, especialmente no que se diz respeito à responsividade.

## 1.2 Quando usar Flexbox?

Utilize o flexbox como se fosse um semáforo. Ele é unidimensional, sendo o ideal para o posicionamento dos itens de um container mais do que os próprios itens, assim acaba com a supremacia do inline-block ou dos floats. Em um container flex o layout é controlado pelo tamanho e altura dos itens flex. Assim, o flex tem como função dizer a direção que os elementos irão se enfileirar e se eles vão quebrar ao atingir as bordas do container.

## 1.3 Diferença entre Flexbox e outras técnicas de layout (Float, Grid, Inline-Block)

### Grid:

Para definir o template de uma página, utilizamos o Grid, delimitando áreas como o header, main e footer, criando o layout onde os elementos vão se encaixar dentro deles, e não o contrário. Sendo assim, fica fácil de redefinir o layout, ajustando o containers grid nas media queries sem ter que ajustar todos os elementos.  
![<gridExample>](<./img/gridExample.webp>)  
Fig1 \- Exemplo: Definindo áreas com grid.

### Uso do flex:

No quesito de enfileirar elementos de quaisquer tamanhos o Flex é o mais apropriado para o serviço. Com ele, temos o container que define a direção na qual os elementos vão se enfileirar e como eles devem se comportar ao atingir as beiradas do container. Ele também define como os itens são alinhados independente do tamanho individual de cada item.
![<gridExample>](<./img/flexExample.webp>)
Exemplo: formatando os compostos com o flex.

### Inline-block

Ele é a junção dos comportamentos inline a qual se baseia em ocupar apenas o espaço do conteúdo e não quebrar linha e block (dimensões configuráveis) em um único elemento HTML. Elementos Inline-Block vão se manter posicionados um ao lado do outro, sem quebras de linhas. Mas te dão a liberdade de atribuir a eles width, height, margin e paddings.

![<gridExample>](<./img/inlineBlockExample.JPG>)  
Exemplo: Demonstrando o uso do inline-block.

### Float

Faz com que o elemento flutue na direção especificada e acima dos outros elementos HTML.

![<gridExample>](<./img/exampleFloat.PNG>)
Exemplo: Demonstrando o uso dos float.