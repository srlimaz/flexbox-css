# Flexbox

### Suporte

Foi projetado como um modelo de layout unidimensional e como um método que pode oferecer distribuição de espaço entre itens em uma interface e recursos de alinhamento.

### Flex Container

É a tag que envolve os itens, será nela que iremos aplicar a propriedade "display: flex". Transforma todos os seus itens filhos em flex itens. 

Pode ser aplicada em qualquer tag.

**Propriedades relacionadas:**

- display: inicializador do container.
- flex-direction: vai fazer o direcionamento desses itens, seja em linha ou em coluna.
- flex-wrap: quebra de linha ou não.
- flex-flow: é uma abreviação para o direction e o wrap.
- justify-content: alinha seu conteúdo de acordo com o seu container de acordo com a sua direção.
- align-items: irá alinhar os itens de acordo com o eixo do container.
- align-content: irá alinhar as linhas do container.

### Flex Item

São os elementos filhos diretos do flex container. E também podem se tornar Flex Container.

**Propriedades relacionadas:**

- flex-grow: define o fator de crescimento.
- flax-basis: define o tamanho inicial do item ante da distribuição do espaço restante dentro do container.
- flex-shrink: define a capacidade de redução.
- flex: abreviação para as 3 propriedades acima.
- order: relacionado a ordem de distribuição e dos itens.
- align-self: define um alinhamento especifico desse container.

**DISPLAY:FLEX;** - Torna a tag um elemento do tipo flex container, e assim automaticamente todos os seus filhos diretos desta tag, tornam-se em flex items. Consegue aplicar em qualquer tag (div, h1,h2...etc).

**FLEX DIRECTION** - É a propriedade que estabelece o eixo principal do container, definindo assim a direção que os flex items são colocados no flex container.

- row: à direção do texto, esquerda para direita.
- row-reverse: sentido oposto à direção do texto.
- column: ordenação de cima para baixo, em coluna única.
- column-reverse: ordenação inversa, de baixo para cima.

**FLEX-WRAP** - É a propriedade que define se os itens devem ou não quebrar a linha. Por padrão eles não quebram linhas, isso faz com que os flex itens sejam compactados além do limite do conteúdo.

- nowrap: é o padrão, não permite a quebra de linha.
- wrap: permite a quebra de linha assim que um dos flex itens não puder mais ser compactado.
- wrap-reverse: permite a quebra de linha assim que um dos flex itens não puder mais ser compactado, porém na direção contrária da linha, acima.

**FLEX-FLOW** - É um atalho para as propriedades _flex-direction_ e _flex-wrap_.

Porém seu uso não é tão comum, visto que, quando mudamos o flex-direction para column, mantemos o padrão do flex-wrap que é nowrap.

**JUSTIFY-CONTENT** - Essa propriedade vai se encarregar de alinhar os itens dentro do container de acordo com a direção pretendida e tratar da distribuição de espaçamento entre eles.

OBS: caso seus itens esteja ocupando 100% de todo o container, ela não se aplica.

- flex-start: inicio do container.
- flex-end: final do container.
- center: ao centro do container.
- space-between: cria um espaçamento igual entre os elementos.
- space-around: os espaçamentos do meio são duas vezes maiores que o inicial e final.

**ALIGN-ITEMS** - Trata do alinhamento dos flex itens de acordo com o eixo do container. 

O alinhamento é diferente para quando os itens estão em colunas ou linhas.

Permite o alinhamento central no eixo vertical.

- center: alinhamento dos itens ao centro.
- stretch: padrão, e os flex itens cresçam igualmente.
- flex-start: alinhamento dos itens no inicio.
- flex-end: alinhamento dos itens no final.
- baseline: alinhamento de acordo com a linha base da tipografia dos itens.

**ALIGN-CONTENT** - Precisamos que:

- O container utilize quebra de linhas.
- A altura do container seja maior que a soma das linhas dos itens.

#

- center: alinhamento dos itens ao centro.
- stretch: é o padrão e os flex itens crescem igualmente.
- flex-start: alinhamento dos itens no inicio.
- flex-end: alinhamento dos itens no final.
- space-between: cria um espaçamento igual entre os elementos.
- space-around: os espaçamentos do meio são duas vezes maiores que o inicial e final.