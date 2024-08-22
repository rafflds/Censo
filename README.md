# Ciência de Dados

**Fonte (adaptado):** https://www.kaggle.com/laotse/credit-risk-dataset


**Exploração dos Dados:**

* Visualização das primeiras linhas do dataset.
* Verificação de tipos de dados.
* Identificação de valores ausentes.
* Estatísticas descritivas.


**Pré-processamento dos Dados:**

* Tratamento de valores ausentes.
* Codificação de variáveis categóricas (se necessário).
* Normalização/Padronização de variáveis numéricas.


**Divisão dos Dados:**

Separação em conjuntos de treino e teste.


**Treinamento de Modelos de Machine Learning:**
Treinamento de um ou mais modelos:
* Regressão Logística
* Árvores de Decisão
* Random Forest, etc.


**Avaliação dos modelos usando métricas apropriadas**

* acurácia, precisão, recall, F1-score.
* Avaliação e Interpretação dos Resultados:


**Análise das métricas de desempenho**
* Discussão dos resultados.
* Exploração dos dados



**O conjunto de dados contém as seguintes colunas:**
* age: Idade do indivíduo.
* workclass: Categoria do tipo de emprego.
* final-weight: Peso final ajustado.
* education: Nível educacional.
* education-num: Número de anos de educação.
* marital-status: Estado civil.
* occupation: Ocupação.
* relationship: Relação familiar.
* race: Raça.
* sex: Sexo.
* capital-gain: Ganho de capital.
* capital-loos: Perda de capital.
* hour-per-week: Horas trabalhadas por semana.
* native-country: País de origem.
* income: Faixa de renda (<=50K ou >50K).


## Verificações:

* **Verificar os tipos de dados.**
  * O dataset tem 15 colunas, sendo 6 delas numéricas (int64) e 9 categóricas (object).
* **Identificar valores ausentes.**
  * Não há valores ausentes em nenhuma coluna.
* **Obter estatísticas descritivas.**
  * <font color=red>Numéricas:
    * A idade varia de 17 a 90 anos.
    * O ganho de capital (capital-gain) varia de 0 a 99999, com uma média de 1077.
    * A perda de capital (capital-loos) varia de 0 a 4356, com uma média de 87.
    * As horas trabalhadas por semana (hour-per-week) variam de 1 a 99, com uma média de 40 horas.
  * Categóricas:
    * A maioria das pessoas trabalha no setor privado (workclass: Private).
    * O nível educacional mais comum é HS-grad.
    * O estado civil mais comum é Married-civ-spouse.
    * A maioria das pessoas é da raça White e do sexo masculino (Male).
    * A maioria das pessoas tem uma renda inferior ou igual a 50K (income: <=50K).





