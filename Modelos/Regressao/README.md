# Modelos de Regressão

Modelos de Regressão são usados para estimar valores continuos, isso é, numeros reais. Por exemplo:

- Preço de uma casa
- Temperatura
- Lucro de uma empresa

**TÓPICOS ABORDADOS**

- [Regresão Linear Simples](linearregression_simple.ipynb)
- [Regressão Linear Múltipla](linearregression_multiple.ipynb)
- [Regressão Polinomial](polynomialregression.ipynb)
- [Regressão Lasso](lassoregression.ipynb)
- [Regressão Ridge](ridgeregression.ipynb)
- [Regressão ElasticNet](elasticnetregression.ipynb)

---

# Dataset de teste

Para o estudo do desenvolvimento de modelos de IA de Regressão não será utilizado um Dataset especifico. 

Já que cada modelo é aplicado em cenários especificos de relação entre as features e os targets, em cada documento será utilizado um dataset diferente, que representa um caso em que o modelo explicado pode ser explorado. 

Dessa forma, pretende-se esclarecer não apenas o desenvolvimento de modeos de Regressão, mas também em quais contextos cada tipo especifico de regressão é aplicado.

---

# Métricas de Avaliação

Modelos de Regressão podem ser avaliados de acordo com:

- [Erro Absoluto Médio - Mean Absolute Error (MAE)](../../Metricas/mean_absolute_error.ipynb)
- [Erro Quadratico Médio - Mean Squared Error (MSE)](../../Metricas/mean_squared_error.ipynb)
- [Raiz do Erro Quadratico Médio - Root Mean Squared Error (RMSE)](../../Metricas/root_mean_squared_error.ipynb)

---

# Projetos

- >Previsão da Espectativa de Vida
  Projeto dedicado a prever a expectativa de vida com diferentes modelos de Regressão (Regressão Linear, Ridge, LASSO, Elasticnet). O projeto utiliza Pipelines para automatizar os processos de Escalonamento e Codificação das Features e treinar os diferentes modelos propostos.   
  **Acesso do Projeto em:** https://github.com/Lin45510/Life_Expectancy_AI

---

[<- Anterior](../PreProcessamento/pipeline_columntransform.ipynb) | [Próximo ->](linearregression_simple.ipynb)