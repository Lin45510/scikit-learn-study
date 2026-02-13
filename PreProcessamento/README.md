[<- Anterior](../README.md) | [Próximo ->](missing_values.ipynb)

# Pré-Processamento de Dados

O Pré-Processamento de dados é uma parte essencial do desenvolvimento de um modelo de IA e se refere à preparação dos dados para que possam ser usados na etapa de treino do modelo.

É importante realizar a etapa de pré-processamento pois o treino de um modelo de IA assume algumas coisas. Por exemplo:

- Os dados de entrada estão em escalas comparáveis.
- Nenhum valor está ausente.
- Os dados utilizados estão nos tipos adequados para realizar os cálculos necessários.

De forma que, não realizar um tratamento prévio nos dados do modelo pode prejudicar a precisão do mesmo.

**TÓPICOS ABORDADOS**
- [Imputação de Valores Nulos ou ausentes](missing_values.ipynb)
  - Valores Numéricos
  - Valores Textuais
- [Escalonamento de Features Numéricas](scaling_normalization.ipynb)
  - Padronização
  - Normalização
- [Codificação de Valores Categóricos](encoding.ipynb)
- [Pipelines e ColumnTransform](pipeline_columntransform.ipynb)
  - Pipelines
  - ColumnTransform
  - Exemplo de Uso de Pipeline e ColumnTransformer

---

# Dataset de teste

Para o estudo do processo de pré-processamento dos dados será utilizado um dataset que possui diferentes tipos de dados e valores nulos. Dessa forma o dataframe de teste pode se aproximar de um caso real e pode ser usado para estudar diferentes ferramentas de pré-processamento.

O dataset utilizado está disponível na pasta Data desse diretório ([aperte aqui para acessar](../Data/PreProcessing_Test.csv)) e possui 100 linhas, apresentando valores nulos nas colunas 'Genero' e 'Salario'. O dataset apresenta uma coluna binaria 'Comprou' que indica se uma pessoa comprou um certo produto

---

[<- Anterior](../README.md) | [Próximo ->](missing_values.ipynb)