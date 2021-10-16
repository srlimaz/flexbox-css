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
- justify-content: alinha seu conteudo de acordo com o seu container de acordo com a sua direção.
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