[<- Anterior](../../Metricas/root_mean_squared_error.ipynb) | [Próximo ->](logisticregression.ipynb)

---

# Clustering

Clustering é um algoritmo de aprendizado de maquina não supervisionado que se baseia no agrupamento de dados a partir de suas semelhanças com o objetivo de descobrir grupos naturais dentro do conjunto de dados mesmo em casos que que esses dados não possam ser rotulados. Esses algoritmos possuem varias funcionalidades e podem ajudar em analises exploratórias e redução de dimencionalidade dos dados à partir da identificação de conjuntos de dados que se assemelhem entre si. Esses modelos podem ser usados para:

- Criar um algoritmo de recomendação de musicas.
- segmentação de mercado.
- Detecção de anomalias e discrepancias como fraude bancaria.

**TÓPICOS ABORDADOS**
- [K-Means]
- [Afinity Propagation]
- [Spectral Clustering]

---

# Dados de Teste

Para o estudo do desenvolvimento de modelos de IA de clusterinz será utilizado o DataSet load_iris, um dataset nativo da biblioteca scikit-learn que contém dados de espécies de flores e suas caracteristicas. O objetivo nesse caso é construir modelos que possam identificar que o conjunto de dados possui três grupos distintos entre sí.

Em uma aplicação real, modelos de clustering trabalham com dados não rotulados. Portanto a coluna 'target' será removida do conjutno de dados.

---

# Métricas de Avaliação

Modelos de clustering podem ser avaliados de acordo com:

- [silhouette_score]

---

# Projetos

Em desenvolvimento...

---

[<- Anterior](../../Metricas/root_mean_squared_error.ipynb) | [Próximo ->](logisticregression.ipynb)