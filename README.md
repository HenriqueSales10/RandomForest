# RandomForest
Este exercício utiliza o conjunto de dados de câncer de mama da biblioteca Scikit-learn para construir e avaliar modelos de classificação com os algoritmos Árvore de Decisão e Random Forest. O objetivo é prever se um tumor é benigno ou maligno com base nas características fornecidas no dataset.

# Descrição do Dataset
O dataset de câncer de mama contém características de tumores (como tamanho, textura, etc.) e um rótulo de diagnóstico: 0 para tumores benignos e 1 para tumores malignos.

Informações do Dataset:
Features: 30 variáveis descritivas de características físicas dos tumores.
Target: Diagnóstico (0 - benigno, 1 - maligno).

# Pré-processamento dos Dados
Para o pré-processamento, o dataset foi dividido em variáveis de entrada (X) e variável alvo (y). Em seguida, os dados foram separados em conjuntos de treino e teste com uma proporção de 70% para treino e 30% para teste. Também verificamos a presença de valores nulos (inexistentes neste dataset).

# Treinamento e Avaliação dos Modelos
Os modelos escolhidos foram Árvore de Decisão e Random Forest. Ambos os modelos foram treinados e, em seguida, avaliados com base em sua precisão, matriz de confusão e relatórios de classificação.

# Conclusão
Neste projeto, o modelo Random Forest obteve maior precisão em comparação com o modelo de Árvore de Decisão, indicando um melhor desempenho na classificação dos tumores benígnos ou malígnos.
