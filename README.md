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