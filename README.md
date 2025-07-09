> 📘 This README is available in: [Português](README.md) | [English](README.en.md)

# Aulas-IA
Um pouco do que desenvolvi durante as aulas de Inteligência Artificial.

---

## 1. Iris DataSet
Executa uma análise exploratória completa do Iris Dataset com foco em visualizações e aplicação de modelo de classificação supervisionada.
### Este notebook inclui:
- Carregamento do Iris Dataset via seaborn e visualização inicial com pandas.
- Exibição de estatísticas descritivas, verificação de dados faltantes e análise da distribuição das classes.
- Visualizações gráficas com matplotlib e seaborn:
  - Histogramas, pairplots, boxplots, violinplots e mapa de correlação (heatmap).
- Separação dos dados em treino e teste com train_test_split.
- Treinamento de um modelo de Regressão Logística com scikit-learn.
- Avaliação do modelo com acurácia, matriz de confusão e relatório de classificação.
- Simulação de predição de uma nova amostra com base em atributos morfológicos.
### Ideal para ilustrar todo o fluxo de preparação e modelagem em problemas de classificação multiclasse com dados estruturados.

---

## 2. Engenharia de Dados
Realiza transformações avançadas de engenharia de dados em um conjunto sintético com variáveis relacionadas à saúde, visando preparar os dados para futuras análises ou modelagem.
### Este notebook inclui:
- Geração de dados fictícios sobre pacientes (idade, sexo, tabagismo, colesterol, etc.).
- Conversão de variáveis contínuas em binárias com base em thresholds clínicos.
- Classificação de variáveis contínuas em faixas categóricas para facilitar segmentações.
- Cálculo de IMC e categorização nutricional com base nos valores.
- Criação de variáveis dummies para codificação binária de atributos categóricos.
- Transformação logarítmica de variáveis assimétricas para normalização estatística.
- Visualização comparativa dos dados originais e transformados por meio de histogramas.
### Ideal para ilustrar boas práticas de preparação de dados em contextos biomédicos e mostrar como diferentes técnicas impactam a estrutura informacional do dataset.

---

## 3. Perceptron
Aplica o algoritmo de classificação supervisionada Perceptron em conjunto com um classificador MLP (Perceptron de múltiplas camadas) para problemas binários reais e sintéticos.
### Este notebook inclui:
- Definição e implementação manual do Perceptron simples com função de ativação Heaviside.
- Criação de dataset sintético com duas classes bem separadas usando NumPy.
- Treinamento do modelo e visualização da fronteira de decisão com Matplotlib.
- Teste de diferentes configurações de taxa de aprendizado (learning rate) e número de épocas.
- Implementação de rede neural MLP com scikit-learn (MLPClassifier) usando o dataset Breast Cancer.
- Padronização dos dados com StandardScaler e divisão com train_test_split.
- Otimização de hiperparâmetros via GridSearchCV para explorar diferentes arquiteturas de rede.
- Avaliação dos modelos com accuracy_score e classification_report.
### Ideal para entender os fundamentos da aprendizagem supervisionada linear, testar variações de parâmetros e aplicar redes neurais simples em problemas reais.

---

## 4. Kmeans
Aplica o algoritmo K-Means para realizar agrupamento não supervisionado em dados químicos do Wine Dataset, buscando padrões naturais entre diferentes cultivares.
### Este notebook inclui:
- Carregamento do Wine Dataset com scikit-learn.
- Padronização das variáveis numéricas com StandardScaler.
- Treinamento do modelo KMeans para separação em 3 clusters.
- Avaliação da qualidade dos agrupamentos com Silhouette Score.
- Redução da dimensionalidade para 2 componentes com PCA.
- Visualização dos clusters obtidos via scatter plot em 2D.
- Comparação opcional com os rótulos reais das amostras para fins ilustrativos.
###Ideal para explorar conceitos de clustering aplicado em dados reais, visualização com redução dimensional e avaliação de agrupamentos por coesão e separação.

---

## 5. Prova 1
Executa um pipeline completo de análise de dados e aprendizado de máquina com base no dataset 'Marketing Campaign', integrando etapas de pré-processamento, clustering e classificação supervisionada.
### Este notebook inclui:
- Carregamento e inspeção inicial de dados reais de clientes.
- Conversão e tratamento de datas, seleção de variáveis relevantes e imputação de dados faltantes.
- Padronização de variáveis numéricas com StandardScaler.
- Redução de dimensionalidade com PCA para facilitar a visualização dos agrupamentos.
- Agrupamento não supervisionado com K-Means:
  - Determinação do número ideal de clusters via Elbow Method.
  - Avaliação da coesão dos clusters com Silhouette Score.
- Geração de pseudo-rótulos a partir dos clusters formados.
- Treinamento de modelo de classificação supervisionada com LogisticRegression.
- Avaliação do desempenho com métricas de acurácia e relatório de classificação.
### Ideal para consolidar conceitos de clustering aplicado em dados reais, engenharia de atributos temporais, uso combinado de aprendizagem supervisionada e não supervisionada, e técnicas de visualização avançada.

---

## 6. Prova 2
Explora técnicas fundamentais de processamento de imagem usando OpenCV em ambiente Google Colab, com aplicação em imagens reais e sintéticas.
### Este notebook inclui:
- Instalação e uso do pacote opencv-python-headless para compatibilidade com Colab.
- Carregamento e exibição de imagens com cv2 e Matplotlib.
- Conversão entre espaços de cor: BGR, RGB, Gray e HSV.
- Geração e comparação de histogramas de intensidade.
- Equalização de histograma para melhorar contraste em imagens.
- Aplicação de filtros de suavização: média, gaussiano e mediana.
- Limiarização global e adaptativa para segmentação binária.
- Detecção de bordas com Canny e extração de contornos com cv2.findContours.
### Ideal para introduzir conceitos práticos de visão computacional e preparar imagens para tarefas como segmentação, reconhecimento e análise visual em projetos de IA.

---

## 7. Classificador Titanic
Executa uma classificação supervisionada para prever a sobrevivência de passageiros a partir do Titanic Dataset, utilizando técnicas estatísticas e modelos de machine learning.
### Este notebook inclui:
- Carregamento do Titanic Dataset via seaborn.
- Exploração dos dados com estatísticas descritivas, visualizações (histogramas, boxplots, pairplots, heatmaps) e análise de valores faltantes.
- Conversão de variáveis categóricas com mapeamento direto.
- Seleção de atributos relevantes para a previsão.
- Divisão dos dados em treino e teste com train_test_split.
- Treinamento de modelo HistGradientBoostingClassifier com scikit-learn.
- Avaliação do modelo com acurácia, matriz de confusão e relatório de classificação.
- Visualização da matriz de confusão com heatmap.
- Geração de entradas aleatórias para simular perfis e realizar previsões detalhadas.
### Ideal para demonstrar um fluxo completo de modelagem supervisionada em dados reais, com foco em engenharia de atributos, avaliação de desempenho e aplicação prática em cenários históricos.
