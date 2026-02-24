# Análise Predição Aderência a Investimentos 

📍 Projeto é de uso pessoal e educacional , desenvolvido através do Curso: `Classificação: aprendendo a classificar dados com Machine Learning`  da  `@Alura` + `@oracle_university`.
Este notebook documenta um projeto de Machine Learning , a análise e predição da aderência de clientes a um programa de investimentos.

## Análise de Aderência a Investimentos

### 1. Obtenção e Exploração dos Dados

### 2. Análise Exploratória de Dados (EDA)

### 3. Pré-processamento dos Dados

### 4. Treinamento e Avaliação de Modelos
- **Divisão de Dados:** Separação dos dados em conjuntos de treino e teste (`x_train`, `x_test`, `y_train`, `y_test`) com `train_test_split`, utilizando estratificação para manter a proporção da variável alvo.
- **Modelo Base (DummyClassifier):** Treinamento e avaliação de um modelo Dummy para estabelecer uma linha de base de desempenho.
- **Árvore de Decisão (DecisionTreeClassifier):**
    - Treinamento inicial de uma árvore de decisão para observar o sobreajuste.
    - Ajuste da árvore de decisão com `max_depth=3` para controlar o sobreajuste, seguida de avaliação nos conjuntos de treino e teste.
    - Visualização da árvore de decisão podada com `plot_tree`.
- **KNN (KNeighborsClassifier):**
    - Normalização dos dados de treino e teste usando `MinMaxScaler`.
    - Treinamento e avaliação do modelo KNN.
- **Comparação de Modelos:** Comparação das acurácias dos modelos Dummy, Árvore de Decisão e KNN.

### 5. Predição de Modelos
- Demonstração de como carregar os modelos salvos e fazer predições com novos dados.

