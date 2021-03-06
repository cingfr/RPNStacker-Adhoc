# RPNStacker Adhoc

Task 01 da cadeira de Compiladores 2021.2, realizada por Gabriel Ferreira Rocha

## Operações Suportadas

Apenas números inteiros positivos são permitidos no input, pegando os valores <img src ="https://latex.codecogs.com/svg.image?A"> e <img src ="https://latex.codecogs.com/svg.image?B"> do topo do stack atual, com as operações:

**(+) Soma:** <img src="https://latex.codecogs.com/svg.image?A%20&plus;%20B">

**(-) Subtração:** <img src="https://latex.codecogs.com/svg.image?A%20-%20B">

**(*) Multiplicação:** <img src="https://latex.codecogs.com/svg.image?A%20%5Ccdot%20B">

**(^) Potência:** <img src="https://latex.codecogs.com/svg.image?A%5E%7BB%7D">

## Como Utilizar:

Colocando o(s) arquivo(s) com a(s) equação/equações na pasta input, basta mudar o valor ```<arquivo>``` na linha

```File input = new File(".//input//<arquivo>");```

do arquivo ```RPNStackerADHOC.java``` para o nome do arquivo que possui a equação desejada. Por _default_, os arquivos tem a extensão ```.stk```.
  
Após isso, basta compilar e executar o código. A saída terá um formato como o seguinte:

<img src ="https://i.imgur.com/XO1W5Y2.png">
  
## Inputs Predefinidos:

Foram colocados 5 arquivos iniciais para demonstrar o código. Seus nomes e equações respectivas são:

**Calc1.stk:** (Resultado = 36)

4

8

\+

3

\*

**Calc2.stk:** (Resultado = 20)

10
  
10
  
\+ 
  
**Calc3.stk** (Resultado = 54)
  
4
  
5
  
\+
  
6
  
\*

**Calc4.stk** (Resultado = 17)
  
2
  
3
  
\*
  
5
  
4
  
\*
  
\+
  
9
  
\-

**Calc5.stk** (Resultado = 49)
  
4
  
5
  
\+
  
2
  
\*
  
10
  
3
  
\-
  
\+
  
18
  
\-
  
2
  
\^
