# ARITMÉTICA
Estudo das operações numéricas.

<br>

## Potência de Base Dez
* É uma representação de números com muitas ordens, ou casas decimais.
* É formado por um número que possui como base o dez, elevado a um expoente inteiro ***n***.
* Tem como resultado para expoente positivo resulta em 1 seguido de ***n*** zeros e para expoente negativo resulta em 1 precedido de ***n*** zeros.

<div style="display:inline_block">
    <img align="left" height="110" width="1000" alt="TypeScript" src="./../../img/sistema-decimal-3.png">
</div>

<br>
<br>
<br>
<br>
<br>
<br>

> #### ADIÇÃO E SUBTRAÇÃO DE POTÊNCIA DE BASE 10
* A adição ou subtração, só ocorre se os expoentes forem iguais.
* Se forem diferentes é preciso iguala-los antes de realizar a operação de soma ou subtração.
* O cálculo é feito repetindo as bases e somando ou subtraindo as partes inteiras.

Ex: 10<sup>4</sup> + 10<sup>4</sup> = 2 . 10<sup>4</sup>  
Ex: 4,1 . 10<sup>3</sup> - 2,1 . 10<sup>3</sup> = 2 . 10<sup>3</sup>  

## Notação Científica
* É uma forma de representar números muito grandes ou muito pequenos usando o produto de potência de base 10.
* Ele é representado por dois fatores:
  - x = a . 10<sup>n</sup>
  - 1º Número decimal ***a***, em que 1 =< a < 10
  - 2º Potência de base 10 com expoente inteiro

> #### CÁLCULO
1. Representa a parte decimal com a vírgula com valor maior que um e menor que dez.
2. Conta o número de casas após a virgula.
3. Para números menores que um o expoente é negativo
4. Para números maiores que um o expoente é positivo

Ex: 24500000 = 2,45 . 10<sup>7</sup>
* 2,4500000 => 2,45 com 7 casas após a vírgula

Ex: 0,000456 = 4,56 . 10<sup>-4</sup>
* 00004,56 => 4,56 a vírgula andou 4 casas pra direita

> #### ORDEM DE GRANDEZA
* É uma estimativa do tamanho da medida de um número.
* Para a . 10<sup>n</sup> a sua ordem de grandeza será:
  - 10<sup>n</sup> se ***a*** < 3,16
  - 10<sup>n + 1</sup> se ***a*** > 3,16
  
Ex: 2,45 = 2,45 . 10<sup>0</sup> ordem de grandeza = 10<sup>0</sup>  
Ex: 34,5 = 3,45 . 10<sup>1</sup> ordem de grandeza = 10<sup>1 + 1</sup> = 10<sup>2</sup>