# oilygiant-well-selection
Projeto de análise e machine learning para selecionar a região mais promissora para novos poços da OilyGiant com base em lucro esperado e risco.

## Visão Geral

Este projeto tem como objetivo apoiar a empresa fictícia **OilyGiant** na escolha da melhor região para a perfuração de novos poços de petróleo. A análise utiliza dados geológicos e um modelo de machine learning para estimar o volume de reservas em diferentes regiões, além de técnicas estatísticas para avaliar lucro esperado e risco de prejuízo.

O foco principal é combinar previsão, viabilidade econômica e análise de risco para recomendar a região com melhor potencial de investimento.

## Problema de Negócio

A OilyGiant precisa decidir em qual região investir na perfuração de novos poços. Como esse tipo de decisão envolve alto custo e incerteza, a empresa precisa de uma análise orientada por dados para identificar a opção com maior retorno esperado e risco aceitável.

Neste projeto, são comparadas diferentes regiões com base em previsões de reservas, cálculo de lucro potencial e avaliação probabilística de perdas.

## Conjunto de Dados

O projeto utiliza dados sintéticos de três regiões potenciais para exploração, contendo características geológicas e o volume de reservas de petróleo associado a cada ponto analisado.

Os arquivos utilizados no projeto estão organizados na pasta `datasets/`:

- `geo_data_0.csv`
- `geo_data_1.csv`
- `geo_data_2.csv`

Cada conjunto de dados contém variáveis explicativas e uma variável-alvo relacionada ao volume estimado de reservas.

## Objetivo do Projeto

Selecionar a região mais promissora para perfuração de novos poços da OilyGiant, combinando previsão do volume de reservas com análise de lucro esperado e risco de prejuízo.

## Objetivos da Análise

Este projeto busca responder perguntas como:

- Qual região apresenta maior potencial de retorno financeiro?
- Qual modelo permite prever melhor o volume de reservas?
- Qual região oferece o melhor equilíbrio entre lucro esperado e risco?
- A probabilidade de prejuízo está dentro do limite aceitável para investimento?

## Etapas do Projeto

O projeto foi desenvolvido nas seguintes etapas:

1. carregamento e inspeção inicial dos dados
2. preparação das variáveis para modelagem
3. treinamento e validação do modelo preditivo
4. previsão do volume de reservas por região
5. cálculo de lucro potencial
6. aplicação de bootstrap para análise de risco
7. comparação entre regiões
8. recomendação final de negócio

## Ferramentas e Bibliotecas

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Estrutura do Repositório

```text
oilygiant-well-selection/
├── .gitignore
├── README.md
├── requirements.txt
├── oilygiant_well_selection.ipynb
└── datasets/
    ├── geo_data_0.csv
    ├── geo_data_1.csv
    └── geo_data_2.csv
````

## Como executar

1. Clone este repositório:

   ```bash
   git clone https://github.com/IagoZanquetta/oilygiant-well-selection.git
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd oilygiant-well-selection
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Abra o arquivo `oilygiant_well_selection.ipynb` no Jupyter Notebook, JupyterLab ou VS Code.

5. Execute as células em ordem.

## Principais Pontos Analisados

Entre os principais focos do projeto, estão:

* previsão de reservas por região
* comparação de desempenho do modelo
* cálculo de lucro esperado
* simulação estatística com bootstrap
* avaliação de risco de prejuízo
* recomendação de investimento com base em dados

## Resultados

Comparação de diferentes regiões com base em modelagem preditiva e análise estatística de risco. Demonstração da possibilidade de converter dados geológicos em recomendação de investimento mais segura, considerando não apenas retorno potencial, mas também a probabilidade de perdas.

O notebook inclui:

* preparação e análise dos dados
* treinamento do modelo preditivo
* estimativas de reservas por região
* cálculo de retorno econômico
* análise de risco com bootstrap
* conclusão com recomendação final

## Conclusão

Este projeto demonstra como técnicas de machine learning e análise estatística podem ser integradas para apoiar decisões de investimento no setor de energia. Ao combinar previsão de reservas com cálculo de lucro e avaliação de risco, a análise permite identificar a região mais promissora para perfuração de novos poços de forma mais segura e fundamentada.

## O que foi aprendido

Desenvolvimento e consolidação de habilidades em:
- modelagem preditiva com regressão
- avaliação de desempenho de modelos
- cálculo de lucro esperado
- aplicação de bootstrap para análise de risco
- tradução de resultados analíticos em recomendação de negócio

## Melhorias Futuras

Possibilidades de evolução do projeto:
- comparar modelos adicionais de regressão
- aprofundar a análise de sensibilidade financeira
- testar diferentes critérios de seleção de poços
- incorporar mais variáveis de negócio ao cálculo de retorno

## Autor

**Iago Zanquetta**

