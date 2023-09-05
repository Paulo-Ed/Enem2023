# ARITMÉTICA
Estudo das operações numéricas.

<br>

## Teoria dos Conjuntos 
* É a teoria matemática que trata do agrupamento de elementos e suas relações.
* Conjuntos, são formados por elementos (qualquer coisa), podendo ser finitos ou infinitos.
* Representação de conjunto:
  - Letra = { elemento1, elemento2, elemento3, elemento4 }

> #### RELAÇÕES ENTRE CONJUNTOS

##### RELAÇÃO DE PERTINÊNCIA
* Indica se um elemento pertence ou não pertence a um determinado conjunto.
* Representação:
  - Elemento ∈ conjunto (pertence)
  - Elemento ∉ conjunto (não pertence)

Ex: B = {1, 2, 3, 4}  
1. 2 ∈ B  
2. 10 ∉ B  

##### RELAÇÃO DE INCLUSÃO
* Indica se um conjunto A está contido no conjunto B, se A não está contido no conjunto B, se se B contem o conjunto A, ou se B não contém o conjunto A.
* Representação:
  - **A** ⊂ **B** (**A** está contido em **B**)
  - **A** ⊄ **B** (**A** não está contido em **B**)
  - **B** ⊃ **A** (**B** contém **A**)
  - **B** ⊅ **A** (**B** não contém **A**)

Ex: A = {1, 2}; B = {1, 2, 3, 4} e C = {11, r}
1. A ⊂ B  
2. C ⊄ B
3. B ⊃ A
4. B ⊅ C

##### CONJUNTO VAZIO
* O conjunto vazio é um conjunto que não possui elementos.
* Representação:
  - {} ou ∅

> #### OPERAÇÕES ENTRE CONJUNTOS

##### UNIÃO DE CONJUNTOS
* Se trata da união de todos os elementos de dois conjuntos em um terceiro conjunto.
* Elementos repetidos só aparecem uma única vez.
* Representação:
  - A ∪ B = AB

Ex: A = {1, 2} e B = {3, 4} 
1. A ∪ B => AB = {1, 2, 3, 4}

##### INTERSECÇÃO DE CONJUNTOS
* Se trata do conjunto formado pelos elementos que se repetem nos dois conjuntos.
* Quando dois conjuntos não possuem elementos em comum, a intersecção entre eles é um conjunto vazio.
* Representação:
  - A ∩ B = C

Ex: A = {1, 2} e B = {1, 2, 3, 4} 
1. A ∩ B => C = {1, 2}

Ex: A = {1, 2} e B = {3, 4} 
1. A ∩ B = {}

##### DIFERENÇA DE CONJUNTOS
* Se trata do conjunto de elementos  que estão no primeiro conjunto, e não estão no segundo conjunto.
* Representação:
  - A - B = C

Ex: A = {1, 2, 10, 15} e B = {1, 2, 3, 4} 
1. A - B => C = {10, 15}

##### IGUALDADE DE CONJUNTOS
* É quando todos os elementos dos conjuntos são iguais.
* Representação:
  - A = B 

Ex: A = {1, 2, 3, 4} e B = {1, 2, 3, 4} 
1. A = B 

##### CONJUNTO COMPLEMENTAR
* O conjunto complementar de **A** é o conjunto do qual **A** faz parte (o conjunto universo) formado pelos elementos que não pertençam a **A**
* Representação:
  - A<sup>C</sup> ou C<sup>A</sup>
  - Se B ⊂ A então A - B = B<sup>C</sup>

Ex: A = {3, 4} e B = {1, 2, 3, 4} 
1. A<sup>C</sup> = {1, 2}

> #### PROPRIEDADES DA UNIÃO E INTERSECÇÃO DE CONJUNTOS

##### COMUTATIVA
* A ∪ B = B ∪ A
* A ∩ B = B ∩ A

##### ASSOCIATIVA
* (A ∪ B) ∪ C = A ∪ (B ∪ C)
* (A ∩ B) ∩ C = A ∩ (B ∩ C)

##### DISTRIBUTIVA
* A ∩(B ∪ C) = (A ∩ B) ∪ (A ∩ C)
* A ∪(B ∩ C) = (A ∪ B) ∩ (A ∪ C)

##### SE A ESTÁ CONTIDO EM B
* A ∪ B = B ⇔ A ∩ B = A
* (A ∪ C) ⊂ (B ∪ C)
* (A ∩ C) ⊂ (B ∩ C)

> #### LEIS DE MORGAN

##### O COMPLEMENTAR DA UNIÃO É IGUAL À INTERSECÇÃO DOS COMPLEMENTARES
* (A ∪ B)<sup>C</sup> = A<sup>C</sup> ∩ B<sup>C</sup>

##### O COMPLEMENTAR DA INTERSECÇÃO É IGUAL À UNIÃO DOS COMPLEMENTARES
* (A ∩ B)<sup>C</sup> = A<sup>C</sup> ∪ B<sup>C</sup>

> #### DIAGRAMA DE VENN
* É uma representação gráfica dos elementos de um conjunto.

<div style="display:inline_block">
    <img align="left" height="200" width="400" alt="TypeScript" src="https://static.todamateria.com.br/upload/di/ag/diagrama1.jpg">
</div>

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

> #### EXEMPLO NÚMERO DE ELEMENTOS DE UM CONJUNTO
Foi feita uma pesquisa entre 100 estudantes de uma escola sobre o consumo de três marcas de refrigerantes: A, B e C. O resultado obtido foi: 38 estudantes consomem a marca A, 30 a marca B, 27 a marca C; 15 consomem a marca A e B, 8 as marcas B e C, 19 as marcas A e C e 4 consomem os três refrigerantes.
Considerando os dados da pesquisa, quantos estudantes consomem apenas uma dessas marcas?

1. Para resolver esse tipo de questão, vamos começar desenhando um diagrama de Venn. Cada marca de refrigerante será representada por um círculo.
2. Vamos começar colocando o número de estudantes que consomem as três marcas simultaneamente, ou seja, a intersecção da marca A,B e C. 
3. Note que o número que consome as três marcas também está embutido no número que consome duas marcas. Então, antes de colocar esses valores no diagrama devemos tirar esses estudantes em comum. 
4. Devemos fazer o mesmo para o número que consome cada marca, pois aí também está repetido as partes comuns.

<div style="display:inline_block">
    <img align="left" height="200" width="400" alt="TypeScript" src="https://static.todamateria.com.br/upload/co/nj/conjunto1.gif?auto_optimize=low">
</div>

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

5. Agora que conhecemos o número de cada parte do diagrama, podemos calcular o número de estudantes que consome apenas uma dessas marcas, somando os valores de cada conjunto. 
6. Nº de pessoas que consome apenas uma das marcas = 11 + 8 + 4 = 23