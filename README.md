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

## Análise dos dados

Analizando os dados adquiridos no preditor de AVC, o valor com o relação mais alta com esse acidente vascular é a hipertensão, que é uma doença que afeta as artérias, seguido por ter um trabalho privado e estarem casados. Os dados encontrados estão abaixo:

`hypertension` 1.9161797751759362
`work_type_Private` 1.2220087468386893
`work_type_Govt_job` 0.8501062047083867
`ever_married_Yes` 0.7942305423397298
`bmi` 0.04353848245863595
`avg_glucose_level` 0.0032088682736495047
`age` -0.023799024835772634
`heart_disease` -0.03574279385007104
`work_type_Never_worked` -0.10596010452077866
`gender` -0.15203185531201022
`smoking_status_smokes` -0.15463364674369248
`Residence_type_Urban` -0.19160052444727962
`smoking_status_formerly smoked` -0.3487340675519495
`work_type_Self-employed` -0.43877985033056516
`work_type_children` -0.8395988620444941
`smoking_status_never smoked` -0.9365968419217553
`smoking_status_Unknown` -1.2835729696956033
 
## Conclusões

- Comparacao dados reais com predicoes

- Divisao entre teste e train usando scikit-learn

- Dados viram numericos, já que são categóricos

- Medir acuracia pegando a quantidade de y^ e vendo se é igual a y, somando todas as vezes em que é igual, e dividindo pelo total de valores