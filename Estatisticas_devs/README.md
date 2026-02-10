# Estatística Descritiva para Ciência de Dados / Descriptive Statistics for Data Science

Estatística Descritiva para o uso em análise de dados, exploração inicial de dados para geração de insights e identificação de padrões. Estas informações podem ser usadas para escolher o modelo de machine learning ideal para a tarefa, para ajustar os parâmetros do modelo e para avaliar o desempenho do modelo.

---

## 🌐 Idiomas / Languages
- [Português](#português)
- [English](#english)

---

<a name="português"></a>
## 🇧🇷 Português

### 1. O que é Estatística?
A estatística é dividida em áreas que permitem transformar dados em conhecimento:
* **Probabilidade:** Estuda as chances de ocorrência de eventos, medindo a incerteza.
* **Estatística Descritiva:** Coleta, organização e resumo de dados para descrever características.
* **Inferência Estatística:** Conclusões sobre uma população com base em uma amostra representativa.

### 2. População e Amostra
* **População:** Conjunto total de elementos com uma característica comum.
* **Amostra:** Subconjunto da população usado quando é inviável analisar o todo.
* **Amostragem:** Processo de seleção da amostra para garantir representatividade.

### 3. Tipos de Variáveis
* **Quantitativas (Numéricas):**
    * **Contínuas:** Valores em um intervalo (ex: Altura, Salário).
    * **Discretas:** Valores inteiros (ex: Idade, Nº de empregados).
* **Qualitativas (Categorias):**
    * **Nominais:** Sem ordem (ex: Sexo, Profissão).
    * **Ordinais:** Com ordem (ex: Escolaridade, Faixa Etária).

### 4. Teorema do Limite Central
É um dos principais teoremas da estatística que diz que, quando você pega várias amostras aleatórias de uma população e calcula a média de cada uma, independentemente da forma da distribuição original, essas médias se aproximam de uma distribuição normal (formato de sino) à medida que o tamanho das amostras aumenta.

**Importância:** Permite fazer inferências sobre a população com base em uma amostra. Por exemplo, se você sabe que a distribuição da média amostral é normal, você pode usar uma tabela de distribuição normal para calcular a probabilidade de que a média amostral seja maior ou menor que um determinado valor.

### 5. Medidas Estatísticas
* **Medidas de Posição:** Indicam o centro dos dados (Média, Mediana, Moda).
* **Medidas de Dispersão:** São ferramentas estatísticas que descrevem o quanto os dados de um conjunto variam em relação à sua média central.
* **Medidas de Formas:** São estatísticas que descrevem a configuração e o contorno da distribuição de um conjunto de dados, permitindo identificar desvios em relação à curva normal padrão.

### 6. Correlação
A correlação na estatística mede a relação entre duas variáveis, indicando se elas têm uma associação linear positiva (aumentam juntas), negativa (uma aumenta enquanto a outra diminui) ou nenhuma correlação.

**Importância para Machine Learning:** Reside na capacidade de identificar padrões e relações entre variáveis. A correlação ajuda a selecionar características relevantes para os modelos, melhorando a precisão e interpretabilidade. Também permite ajustar modelos para prever com maior acurácia com base nas relações observadas nos dados.

---

<a name="english"></a>
## 🇺🇸 English

### 1. What is Statistics?
Statistics is divided into key areas that transform raw data into knowledge:
* **Probability:** The study of the likelihood of events occurring and the measurement of uncertainty.
* **Descriptive Statistics:** The collection, organization, and summarization of data to describe its core characteristics.
* **Statistical Inference:** The process of drawing conclusions about a population based on a representative sample.

### 2. Population and Sample
* **Population:** The complete set of elements sharing a common characteristic.
* **Sample:** A subset of the population used when it is unfeasible to analyze the whole.
* **Sampling:** The specific process of selecting a sample to ensure it accurately represents the population.

### 3. Types of Variables
* **Quantitative (Numerical):**
    * **Continuous:** Values within a range (e.g., Height, Salary).
    * **Discrete:** Countable integer values (e.g., Age, Number of employees).
* **Qualitative (Categorical):**
    * **Nominal:** Categories without an inherent order (e.g., Gender, Profession).
    * **Ordinal:** Categories with a logical order or ranking (e.g., Education Level, Age Group).



### 4. Central Limit Theorem
The Central Limit Theorem (CLT) is a fundamental concept in statistics. It states that when multiple random samples are taken from a population, the distribution of their means will approach a **normal distribution** (bell curve) as the sample size increases, regardless of the original population's distribution shape.

**Importance:** It allows for population-level inferences based on a sample. Because the sample mean distribution is normal, you can use a normal distribution table to calculate the probability of a sample mean being greater or less than a specific value.



### 5. Statistical Measures
* **Measures of Position (Central Tendency):** Indicators of the data's center (Mean, Median, Mode).
* **Measures of Dispersion:** Statistical tools that describe how much the data varies in relation to the mean (e.g., Variance, Standard Deviation).
* **Measures of Shape:** Statistics that describe the configuration and outline of a dataset's distribution, identifying deviations (such as skewness) from the standard normal curve.

### 6. Correlation
Correlation measures the relationship between two variables, indicating whether they have a:
* **Positive correlation:** Both variables increase together.
* **Negative correlation:** One variable increases while the other decreases.
* **No correlation:** No linear relationship exists between the variables.

**Importance for Machine Learning:** Correlation is essential for identifying patterns and relationships between variables. It assists in **feature selection**, helping to choose the most relevant variables for a model to improve precision and interpretability. It also allows for model adjustments to predict outcomes with greater accuracy based on observed data relationships.
