# MATEMÁTICA

<br>

## Análise Combinatória

> #### PRINCÍPIO FUNDAMENTAL DA CONTAGEM
* Também chamado de princípio multiplicativo, define que em um evento, com n etapas, em que para cada etapa exista uma quantidade de opções de resultados (Elementos), o número total de possibilidades que formam o evento, é o produto do número das opções de cada etapa do evento.
Ex: 5 camisas, 3 calças e 2 sapatos

etapa 1 => 5
etapa 2 => 3
etapa 3 => 2

número de possibilidades = 5 . 3 . 2 = 30 

> #### FATORIAL
* O fatorial de um número é o produto deste número por todos os seus antecessores.
* Representação:
  - n!
  - n! = n . (n - 1) . (n - 2) . ... (n - (n - 1))! 

Ex: 0! = 1  
Ex: 1! = 1  
Ex: 2! = 2 . 1 = 2  
Ex: 3! = 3 . 2 . 1 = 6  
Ex: 4! = 4 . 3 . 2 . 1 = 24  

OBS: Em uma razão, o fatorial pode ser eliminado, igualando-se o numerador ao denominador.

Ex: 4!/3! = 4 . 3!/3! = 4  

> #### ARRANJO
* Agrupamento de elementos em que a ordem importa, sendo o número de etapas igual ou menor que o número de opções. A característica dos elementos também importa. (característica para etapa)
* Fórmula: 
  - A<sub>n,p</sub>= n!/(n - p!)
  - n = Total de opções
  - p = Total de etapas

> #### PERMUTAÇÃO
* É um agrupamento em que a ordem importa e o número de etapas é igual ao número de opções.
* A permutação é um tipo de arranjo.
* Fórmula: 
  - P<sub>n</sub>= n!
  - n = Total de opções

##### PERMUTAÇÃO SIMPLES
* Ordenação dos elementos em que não pode haver repetição (são distintos para cada etapa).

##### PERMUTAÇÃO COM REPETIÇÃO
* Ordenação dos elementos em que alguns elementos podem se repetir em etapas diferentes.

##### PERMUTAÇÃO CIRCULAR
* Ordenação dos elementos em que alguns elementos podem se repetir em etapas diferentes.
* Fórmula: 
  - PC<sub>n</sub>= (n - 1)!
  - n = Total de opções

> #### COMBINAÇÃO
* É um agrupamento em que a ordem não importa, sendo o número de etapas igual ou menor que o número de opções. Apenas a caracteristica dos elementos importa (caracteristica para etapa).
* Fórmula: 
  - C<sub>n</sub>= n!
  - n = Total de opções

> #### PRINCÍPIO DA CASA DOS POMBOS
* Para 10 casas em que 11 pombos vão entrar, uma casa com certeza terá no mínimo 2 pombos. 
* Define assim que, para um evento com mais opções por etapa do que etapas, uma das etapas terá no mínimo uma opção repetida.
* É usado para determinar o número mínimo de etapas em um evento para atender com 100% de certerza uma determinada condição.

##### RESOLUÇÃO
1. Para resolver questões desse tipo, começa-se pela ideia de pior coisa que pode acontecer antes de atender a condição (máximo de vezes de não atender a condição) e a quantifica.
2. O resultado será o número dessas possibilidades (que não atendem a condição na pior situação), com a próxima possibilidade de atender a condição.