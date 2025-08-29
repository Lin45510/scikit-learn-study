![Status](https://img.shields.io/badge/status-em%20desenvolvimento-red.svg)

# Documentação de Estudos da Biblioteca scikit-learn

Esse diretório tem o objetivo de documentar o meu aprendizado na biblioteca scikit-learn, uma biblioteca utilizada para o desenvolvimento de modelos de Machine Learning em Pyhton. A proposta é abordar desde os fundamentos básicos até conceitos mais avançados como:

- Pré-processamento de dados.
- Diferentes modelos de IA e suas aplicações.
- Boas praticas de desenvolvimento.
- Automação de tarefas relacionadas a IA.

Além disso, ao tornar essas anotações publicas, pretende-se que outras pessoas interessadas em estudar a biblioteca possam utilizar esse diretório para estudo e consultas, promovendo uma melhor compreensão da biblioteca e dos fundamentos envolvidos na sua aplicação através de anotações detalhadas e didáticas sobre o seu uso.

Para cumprir com os objetivos propostos, serão utilizados Jupyter Notebooks. Essa ferramenta permite a criação de explicações mais bem estruturadas, facilitando a leitura e compreensão dos temas abordados, já que é possível separar o código das explicações, além de criar diferentes tópicos dentro de um mesmo documento. Apesar disso, todos os códigos serão comentados para promover um melhor entendimento da execução de cada linha.

Além disso o diretório conta com uma organização que facilita a navegação pelos tópicos abordados, dessa forma, é mais fácil encontrar os tópicos que se deseja estudar. Veja abaixo uma representação de como o diretório está organizado:

scikit-learn-study   
├── [Data](/Data/)   
│   ├── [preprocessing_test.csv](/Data/preprocessing_test.csv)   
│   ├── [multilinearregression.csv](/Data/multilinearregression.csv)   
├── [Metricas](/Metricas/)   
│   ├── [mean_absolute_error.ipynb](/Metricas/mean_absolute_error.ipynb)   
│   ├── [mean_squared_error.ipynb](/Metricas/mean_squared_error.ipynb)     
│   ├── [README.md](/Metricas/README.md)   
│   ├── [root_mean_squared_error.ipynb](/Metricas/root_mean_squared_error.ipynb)     
├── [Modelos](/Modelos/)   
│   ├── [Regressao](/Modelos/Regressao/)   
│   │   ├── [elasticnetregression.ipynb](/Modelos/Regressao/elasticnetregression.ipynb)  
│   │   ├── [lassoregression.ipynb](/Modelos/Regressao/lassoregression.ipynb)    
│   │   ├── [linearregression_multiple.ipynb](/Modelos/Regressao/linearregression_multiple.ipynb)   
│   │   ├── [linearregression_simple.ipynb](/Modelos/Regressao/linearregression_simple.ipynb)   
│   │   ├── [polynomialregression.ipynb](/Modelos/Regressao/polynomialregression.ipynb)   
│   │   ├── [README.md](/Modelos/Regressao/README.md)    
│   │   ├── [ridgeregression.ipynb](/Modelos/Regressao/ridgeregression.ipynb) 
│   ├── [README.md](/Modelos/README.md)   
├── [PreProcessamento](/PreProcessamento/)   
│   ├── [encoding.ipynb](/PreProcessamento/encoding.ipynb)   
│   ├── [missing_values.ipynb](/PreProcessamento/missing_values.ipynb)   
│   ├── [pipeline_columntransform.ipynb](/PreProcessamento/pipeline_columntransform.ipynb)   
│   ├── [README.md](/PreProcessamento/README.md)   
│   ├── [scaling_normalization.ipynb](/PreProcessamento/scaling_normalization.ipynb)   
├── [Validacao](/Validacao/)   
│   ├── [cross_validation.ipynb](/Validacao/cross_validation.ipynb)    
│   ├── [README.md](/Validacao/README.md)    
│   ├── [train_test_split.ipynb](/Validacao/train_test_split.ipynb)  
├── [README.md](/README.md)     

---

# Dica para ordem de leitura

1. [Introdução do Diretório](/README.md)
2. [Pré-Processameto](/PreProcessamento/README.md)
3. [Valores Ausentes ou Nulos](/PreProcessamento/missing_values.ipynb)
4. [Padronização e Normalização](/PreProcessamento/scaling_normalization.ipynb)
5. [Codificação](/PreProcessamento/encoding.ipynb)
6. [Pipeline e ColumnTransform](/PreProcessamento/pipeline_columntransform.ipynb)
7. [Validação](/Validacao/README.md)
8. [Dataset de Treino e Dataset de Teste](/PreProcessamento/train_test.ipynb)
9. [Validação Cruzada](/Validacao/cross_validation.ipynb)
10. [Modelos](/Modelos/README.md)
11. [Regressão](/Modelos/Regressao/README.md)
12. [Regressão Linear Simples](/Modelos/Regressao/linearregression_simple.ipynb)
13. [Regressão Linear Multipla](/Modelos/Regressao/linearregression_multiple.ipynb)
14. [Regressão Polinomial](/Modelos/Regressao/polynomialregression.ipynb)
15. [Regressão LASSO](/Modelos/Regressao/lassoregression.ipynb)
16. [Regressão Ridge](/Modelos/Regressao/ridgeregression.ipynb)
17. [Regressão ElasticNet](/Modelos/Regressao/elasticnetregression.ipynb)
18. [Métricas de Avaliação](/Metricas/README.md)
19. [Erro Absoluto Médio](/Metricas/mean_absolute_error.ipynb)
20. [Erro Quadrático Médio](/Metricas/mean_squared_error.ipynb)
21. [Raiz do Erro Quadrático Médio](/Metricas/root_mean_squared_error.ipynb)

---

# NOTAS
Essa seção é dedicada a apresentar esclarecimentos sobre certos aspectos do diretório com o objetivo de explicar algumas características que possam gerar duvidas entre pessoas que façam uso dos materiais aqui postados.

1. Com o objetivo de facilitar a compreensão dos temas abordados, cada pasta deste diretório possui um README próprio, que serve como uma introdução ao tema que será tratado pelos documentos.
  
2. Os notebooks disponíveis possuem nomes em inglês. Isso acontece por que a linguagem de markdown não reconhece pontuações, o que impede que documentos ou tópicos com acentuação no nome possam ser referenciados de forma navegável. Ainda assim, os tópicos com nome em português tratados nos notebooks podem ser encontrados na sessão ["Dica para ordem de Leitura"](#dica-para-ordem-de-leitura) do README principal.

3. Os códigos e textos presentes tanto nos Notebooks quanto nos documentos desse repositório **NÃO CONTAM COM O USO DE INTELIGENCIA ARTIFICIAL**. Porém, com o objetivo de tornar o projeto mais transparente, qualquer eventual uso de IA será **EXPLICITAMENTE** citado sempre que for realizado, contando ainda com uma revisão para evitar erros provenientes do uso dessas ferramentas.

4. Os notebooks e documentos desse projeto possuem elementos navegáveis marcados como 'Anterior' e 'Próximo'. Esses elementos tem o objetivo de realizar uma navegação seguindo a ordem de leitura recomendada na sessão ["Dica para ordem de Leitura"](#dica-para-ordem-de-leitura) do README principal.

---
 | [Próximo ->](/PreProcessamento/README.md)