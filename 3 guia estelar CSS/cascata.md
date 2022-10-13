Seu estilo é lido de cima para baixo, ou seja, caso haja algum selector com informações conflitantes, o mais embaixo é o que será atribuído.
São levados em consideração 3 fatores:

# A origem do estilo;
Inline > tag style > tag link

# A especificidade;
É um cálculo matemático, onde cada tipo de seletor e origem do estilo possuem valores a serem considerados.

0. Universal selector, combinators e negation pseudo-class (:not())
1. Element type selector e pseudo-elements (::before, ::after)
10. Classes e attribute selectors ([type="radio"])
100. ID selector
1000. Inline

# A importância;
sintaxe: !important
* cuidado, evite o uso
* não é considerado uma boa prática
* quebra o fluxo natural da cascata
