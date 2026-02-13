![Status](https://img.shields.io/badge/status-em%20desenvolvimento-red.svg)

# Documentação de Estudos da Biblioteca scikit-learn

Esse diretório tem o objetivo de documentar o meu aprendizado na biblioteca scikit-learn, uma biblioteca utilizada para o desenvolvimento de modelos de Machine Learning em Python. A proposta é abordar desde os fundamentos básicos até conceitos mais avançados como:

- Pré-processamento de dados.
- Diferentes modelos de IA e suas aplicações.
- Otimização.
- Validação de modelos.
- Boas praticas de desenvolvimento.
- Automação de tarefas relacionadas a IA.

Além disso, ao tornar essas anotações publicas, pretende-se que outras pessoas interessadas aprender mai sobre essa biblioteca possam utilizar esse diretório para estudo e consultas, promovendo uma melhor compreensão da biblioteca e dos fundamentos envolvidos na sua aplicação.

Para cumprir com os objetivos propostos, serão utilizados Notebooks. Essa ferramenta permite a criação de explicações mais bem estruturadas, facilitando a leitura e compreensão dos temas abordados, já que é possível separar o código das explicações, além de criar diferentes tópicos dentro de um mesmo documento. Apesar disso, todos os códigos serão comentados para promover um melhor entendimento da execução de cada linha.

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
│   │   ├── [elasticnetregression.ipynb](/Modelos/Regressao/elasticnet.ipynb)  
│   │   ├── [lassoregression.ipynb](/Modelos/Regressao/lasso.ipynb)    
│   │   ├── [linearregression_multiple.ipynb](/Modelos/Regressao/linearregression_multiple.ipynb)   
│   │   ├── [linearregression_simple.ipynb](/Modelos/Regressao/linearregression_simple.ipynb)   
│   │   ├── [polynomialregression.ipynb](/Modelos/Regressao/polynomialregression.ipynb)   
│   │   ├── [README.md](/Modelos/Regressao/README.md)    
│   │   ├── [ridgeregression.ipynb](/Modelos/Regressao/ridge.ipynb)   
│   ├── [README.md](/Modelos/README.md)   
├── [PreProcessamento](/PreProcessamento/)   
│   ├── [encoding.ipynb](/PreProcessamento/encoding.ipynb)   
│   ├── [missing_values.ipynb](/PreProcessamento/missing_values.ipynb)   
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
6. [Modelos](/Modelos/README.md)
7. [Regressão](/Modelos/Regressao/README.md)
8. [Regressão Linear Simples](/Modelos/Regressao/linearregression_simple.ipynb)
9. [Regressão Linear Multivariada](/Modelos/Regressao/linearregression_multiple.ipynb)
10. [Regressão Linear Polinomial](/Modelos/Regressao/polynomialregression.ipynb)
11. [Regressão Linear LASSO](/Modelos/Regressao/lasso.ipynb)
12. [Regressão Linear RIDGE](/Modelos/Regressao/ridge.ipynb)
13. [Regressão Linear Elastic NET](/Modelos/Regressao/elasticnet.ipynb)
14. [Validação](/Validacao/README.md)
15. [Divisão de Treino e Teste](/Validacao/train_test_split.ipynb)
16. [Validação Cruzada](/Validacao/cross_validation.ipynb)
17. [Métricas de Avaliação](/Metricas/README.md)
18. [Erro Qudratico Absoluto](/Metricas/mean_absolute_error.ipynb)
19. [Erro Quadratico Médio](/Metricas/mean_squared_error.ipynb)
20. [Raiz do Erro Quadratico Médio](/Metricas/root_mean_squared_error.ipynb)

---

# Registro de Atualizações e Mudanças

- **12/02/2026:**
  
  - Reformulei as explicações para os modelos de Regressão Linear e dos processos de Pré-Processamneto de dados, Validação e Avaliação.
  - Alterei a ordem de recomendação de leitura, o objetivo agora é explicar cada Modelo de Inteligencia artificial e em seguida abordar as métricas que melhor se enquadram para sua avaliação. A ordem também foi corrigida nos botões 'próximo' e 'Anterior' No cabeçalho e no Rodapé dos documentos.
  - Removi referêncais de sessões especificas dentro de um mesmo documento, motivo: Apenas funciona localmente mas apresenta problemas no github.
  - Removi temporariamente os modelos de Classificação para reformular suas explicações.

---

# NOTAS
Essa seção é dedicada a apresentar esclarecimentos sobre certos aspectos do diretório com o objetivo de explicar algumas características que possam gerar duvidas entre pessoas que façam uso dos materiais aqui postados.

1. Com o objetivo de facilitar a compreensão dos temas abordados, cada pasta deste diretório possui um README próprio, que serve como uma introdução ao tema que será tratado pelos documentos.
  
2. Os notebooks disponíveis possuem nomes em inglês. Isso acontece por que a linguagem de markdown não reconhece pontuações, o que impede que documentos ou tópicos com acentuação no nome possam ser referenciados de forma navegável. Ainda assim, os tópicos com nome em português tratados nos notebooks podem ser encontrados na sessão **"Dica para ordem de Leitura"** do README principal.

3. Os códigos e textos presentes tanto nos Notebooks quanto nos documentos desse repositório **NÃO CONTAM COM O USO DE INTELIGENCIA ARTIFICIAL**. Porém, com o objetivo de tornar o projeto mais transparente, qualquer eventual uso de IA será **EXPLICITAMENTE** citado sempre que for realizado, contando ainda com uma revisão para evitar erros provenientes do uso dessas ferramentas.

4. Os notebooks e documentos desse projeto possuem elementos navegáveis marcados como 'Anterior' e 'Próximo'. Esses elementos tem o objetivo de realizar uma navegação seguindo a ordem de leitura recomendada na sessão **"Dica para ordem de Leitura"** do README principal.

---
 | [Próximo ->](/PreProcessamento/README.md)