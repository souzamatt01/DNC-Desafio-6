# DNC-Desafio-6

Sexta prova da formação em Cientista de Dados pela Escola DNC

**Arquivo da Base de Dados utilizada :** https://1drv.ms/x/c/69e90b17d093c171/ER9FLc_cQwVEh3vTFcdcwmkBj81ypvjviPlmMhGYZqCjUQ?e=DE3N0L

**Contexto:** Você trabalha em uma plataforma de streaming e a diretoria está preocupada com o alto índice de usuários cancelando as suas assinaturas. Eles acreditam que é possível prever se um usuário tem mais chance de deixar a plataforma antes que isso aconteça, e com base nessa informação tomar ações para reduzir o churn.

Seu objetivo é criar um modelo de classificação capaz de prever se um usuário tem mais chance de cancelar a sua assinatura na plataforma ou não. Para isso, a empresa forneceu uma base de dados em csv contendo dados sobre as contas dos clientes.

**Critérios de Avaliação:**
- **Data Understanding:** Para esta etapa os alunos precisam trabalhar a base de dados para entender com estão as distribuição dos dados, para isso eles precisam fazer as etapas: Describe, Info, isna().sum().
- **Data Preparation:** Para esta etapa os alunos precisam preparar a base de dados para realizar posteriormente a etapa de modelagem, para isso eles precisam utilizar minimamente as seguintes funções: fillna(), dropna, replace, astype(int), ou seja, substituição de valores, exclusão de valores, troca de valores, mudança de tipo de dado.
- **Modeling - Regressão Logística:** Para esta etapa os alunos precisam modelar a base de dados para.  Eles precisam utilizar minimamente as seguintes funções: LabelEncoder, .fit, .transform, get_dummies, MinMaxScaler, train_test_split, predict, assign, ConfusionMatrixDisplay.
- **Modeling - Tunning:** Para essa etapa os alunos precisam tunar os modelos e utilizar minimamente as seguintes funçoes para atingir uma acurácia maior: grid_search.best_estimator_.get_params(), fit, assign, ConfusionMatrixDisplay.
- **Modeling - Radom Forest:** Para esta etapa os alunos precisam modelar a base de dados para.  Eles precisam utilizar minimamente as seguintes funções: LabelEncoder, .fit, .transform, get_dummies, MinMaxScaler, train_test_split, predict, assign, ConfusionMatrixDisplay.

  **Código comentado no Google Colab se encontra disponível dentro desse Repositório.**
