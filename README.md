# AVC Classifier Avaliation

APS 6 - Algebra Linear e Teoria da Informação - 2023.1

## Integrantes do grupo
* [Pedro Antônio](https://github.com/P-ASilva)
* [Gustavo Lindenberg](https://github.com/gustavolp1)
* [Julia Karine](https://github.com/Juliakp1)

# Índice
1. [Introdução](#introdução)
2. [Como rodar](#como-rodar)
3. [Funcionamento do sistema preditor de notas](#funcionamento-do-sistema-preditor-de-notas)

## Introdução

Por meio de classificadores, é possível determinar resultados a partir de dados específicos. Este projeto possui o objetivo de avaliar um classificador de fatores de risco para o acidente vascular cerebral (AVC). Ou seja, qualquer fator que aumente o risco de um indivíduo ter uma casualidade como essa impacta o resultado.



## Como rodar

Requerimentos:
- IDE (sua escolha)
- Python
- pip
    - numpy
    - sklearn

Arquivo a rodar no IDE:
- demo.py
    - Necessário abrir o folder no explorer para acessar as funções

## Funcionamento do sistema preditor de notas

- Comparacao dados reais com predicoes

- Divisao entre teste e train usando scikit-learn

- Dados viram numericos, já que são categóricos

- Medir acuracia pegando a quantidade de y^ e vendo se é igual a y, somando todas as vezes em que é igual, e dividindo pelo total de valores