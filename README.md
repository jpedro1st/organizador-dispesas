# Organizador de Despesas Pessoais — Bubble Sort

## Instituição
UDF — Centro Universitário do Distrito Federal

## Disciplina
Algoritmos e Pensamento Computacional

## Professora
Profa. Karla R. Sartin

## Integrantes
- Arthur Teodoro Severo
- Joao Pedro Santos da Silva

## 1. Descrição do problema

O controle financeiro pessoal exige a organização das
despesas para facilitar a identificação dos maiores gastos.
Quando os valores estão desorganizados, pode ser mais
difícil identificar quais despesas merecem atenção.

## 2. Objetivo

Desenvolver uma aplicação em linguagem C que organize
10 despesas pessoais em ordem decrescente, utilizando
o algoritmo Bubble Sort.

## 3. Funcionamento do Bubble Sort

O Bubble Sort compara elementos adjacentes de um array
e realiza trocas quando estão fora da ordem desejada.

Neste projeto, a ordenação é decrescente. Portanto, quando
o elemento atual é menor que o próximo, os valores são
trocados utilizando uma variável temporária.

O processo é repetido até que todas as despesas estejam
ordenadas do maior valor para o menor.

## 4. Tecnologias e ferramentas

- Linguagem C
- Compilador GCC
- Git
- GitHub
- Visual Studio Code ou outro editor de código

## 5. Como compilar

Com o GCC instalado, execute no terminal:

gcc main.c -o despesas

## 6. Como executar

No Linux:
./despesas

No Windows:
despesas.exe

## 7. Exemplo de dados

Entrada: valores de despesas definidos no array do programa.

Valores originais:
150.00, 45.90, 320.00, 89.50, 210.75,
35.00, 500.00, 120.00, 75.25, 180.00

Saída esperada:
500.00, 320.00, 210.75, 180.00, 150.00,
120.00, 89.50, 75.25, 45.90, 35.00

## 8. Considerações finais

O projeto permitiu aplicar conceitos de arrays, variáveis,
estruturas condicionais e laços de repetição em linguagem C.

A implementação do Bubble Sort demonstrou como comparar
e trocar elementos adjacentes para organizar dados reais.
