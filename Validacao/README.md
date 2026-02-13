[<- Anterior](../Modelos/Regressao/elasticnet.ipynb)  |  [Proximo ->](train_test_split.ipynb)

# Técnicas de Validação

A validação de um modelo de inteligencia artificial é o processo que visa avaliar o desempenho do modelo. Isso é feito comparando os resultados gerados pelo modelo treinado com os resultados esperados e essa comparação é realizada através de [métricas de avaliação](/Metricas/README.md).

A validaçã de um modelo consiste portanto na criação de dois tipos distintos de conjutnos de dados:

- **Conjunto de Treino** -> Dados usados para treinar um modelo, isso é, dados em que o modelo busca padrões e aprende.
- **Conjunto de Teste** -> Dados usados para avaliar um modelo, isso é, dados usados para testar a precisão do modelo frente a novos dados.

Essa divisão é necessária pois, ao avaliar um modelo com os mesmos dados utilizados para treina-lo podemos obter uma perspectiva falha sobre sua precisão, ja que, ao invés de aprender o modelo pode acabar decorando os dados, o que o torna falho em previsões realizadas com novos dados. Esse fenômeno é chamado de **Overfitting**.

Técnicas de Validação são técnicas usadas para criar diferentes conjuntos de dados à partir do dataset que será utilizado para treinar um modelo. Dessa forma, ao menos parte dos dados podem ser usados para a avaliação do modelo.

> Esse processo é normalmente realizado apenas após a etapa de [Pré-Processamento](../PreProcessamento/README.md)

# Dados de teste

Para simular uma situação de validação de um modelo será utilizado um Dataset ficticio com dados sobre preço de carros de forma que o preço de um veiculo possa ser associado aos demais valores apresentados como: ano, km_rodados, num_portas.

O dataset utilizado está disponível na pasta Data desse diretório [(aperte aqui para acessar)](../Data/multilinearregression.csv) e possui 100 linhas, com valores numéricos e nenhum elemento nulo, de forma que o processo de imputing não é necessário.

---

**TÓPICOS ABORDADOS**

- [Divisão de Treino e Teste](train_test_split.ipynb)
- [Validação Cruzada](cross_validation.ipynb)

---
[<- Anterior](../Modelos/Regressao/elasticnet.ipynb)  |  [Proximo ->](train_test_split.ipynb)