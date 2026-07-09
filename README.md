# 🏥 Sistema Inteligente de Apoio ao Diagnóstico de Diabetes
### Tech Challenge – Fase 1 | Pós-Graduação em Inteligência Artificial – FIAP

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)
![FIAP](https://img.shields.io/badge/FIAP-Tech%20Challenge-red)

---

# 📖 Sobre o Projeto

Este projeto foi desenvolvido como parte do **Tech Challenge – Fase 1** da Pós-Graduação em **Inteligência Artificial da FIAP**.

O desafio consiste em desenvolver a base de um sistema inteligente capaz de apoiar o diagnóstico clínico utilizando técnicas de **Ciência de Dados**, **Machine Learning** e **Inteligência Artificial**.

Para isso, foi utilizado o **Pima Indians Diabetes Dataset**, um conjunto de dados amplamente empregado em pesquisas acadêmicas e aplicações de classificação na área da saúde.

O projeto contempla todo o fluxo de desenvolvimento de um problema supervisionado de classificação, desde a compreensão do problema de negócio até a avaliação crítica dos modelos de Machine Learning, seguindo boas práticas utilizadas em projetos reais de Ciência de Dados.

---

# 🎯 Objetivos

Os principais objetivos deste projeto são:

- compreender o problema proposto pelo desafio;
- realizar uma Análise Exploratória de Dados (EDA);
- avaliar a qualidade do conjunto de dados;
- identificar inconsistências e valores inválidos;
- realizar o tratamento e pré-processamento dos dados;
- construir um Pipeline de Machine Learning;
- comparar diferentes algoritmos de classificação;
- avaliar os modelos utilizando métricas adequadas ao contexto clínico;
- interpretar os resultados obtidos;
- discutir limitações e possíveis evoluções do projeto.

---

# 🩺 Dataset

Foi utilizado o **Pima Indians Diabetes Dataset**, um dos conjuntos de dados mais utilizados em estudos de classificação supervisionada para apoio ao diagnóstico de diabetes.

## Características do Dataset

| Característica | Valor |
|----------------|------:|
| Total de registros | 768 |
| Número de atributos preditores | 8 |
| Variável alvo | Outcome |
| Tipo do problema | Classificação Binária |

O objetivo consiste em prever se uma paciente apresenta ou não diabetes com base em informações clínicas coletadas durante exames médicos.

---

# 📋 Estrutura das Variáveis

| Variável | Descrição |
|----------|-----------|
| Pregnancies | Número de gestações |
| Glucose | Concentração de glicose plasmática |
| BloodPressure | Pressão arterial diastólica |
| SkinThickness | Espessura da dobra cutânea do tríceps |
| Insulin | Nível de insulina sérica |
| BMI | Índice de Massa Corporal |
| DiabetesPedigreeFunction | Indicador de histórico familiar de diabetes |
| Age | Idade da paciente |
| Outcome | Diagnóstico de diabetes (0 = Não diabético / 1 = Diabético) |

---

# 🔬 Metodologia

O desenvolvimento do projeto seguiu a metodologia **CRISP-DM (Cross Industry Standard Process for Data Mining)**, amplamente utilizada em projetos de Ciência de Dados.

As etapas desenvolvidas foram:

1. Entendimento do Problema
2. Entendimento dos Dados
3. Preparação dos Dados
4. Modelagem
5. Avaliação

Durante o desenvolvimento foram aplicadas boas práticas de Ciência de Dados e Engenharia de Machine Learning, incluindo:

- Análise Exploratória de Dados (EDA);
- identificação de inconsistências nos dados;
- tratamento de valores iguais a zero considerados ausentes;
- imputação utilizando a mediana;
- construção de Pipeline para pré-processamento;
- prevenção de Data Leakage;
- divisão estratificada entre treino e teste;
- validação cruzada estratificada;
- comparação entre diferentes algoritmos de classificação;
- interpretação dos resultados obtidos.

---

# 🔄 Fluxo do Projeto

O desenvolvimento seguiu o seguinte fluxo metodológico:

```text
Entendimento do Problema
            │
            ▼
Entendimento dos Dados
            │
            ▼
Análise Exploratória (EDA)
            │
            ▼
Tratamento dos Dados
            │
            ▼
Pipeline de Pré-processamento
            │
            ▼
Treinamento dos Modelos
            │
            ▼
Avaliação dos Modelos
            │
            ▼
Discussão dos Resultados
            │
            ▼
Conclusões
```

Esse fluxo garante maior organização, reprodutibilidade e reduz o risco de vazamento de informações entre os conjuntos de treinamento e teste.

---

# 📊 Etapas Desenvolvidas

O notebook contempla todas as etapas previstas para esta fase do projeto.

## Entendimento dos Dados

- Compreensão do problema de negócio;
- Caracterização do conjunto de dados;
- Identificação da variável alvo.

## Análise Exploratória (EDA)

- Estatística descritiva;
- Distribuição da variável alvo;
- Histogramas;
- Boxplots;
- Análise de assimetria;
- Análise de curtose;
- Identificação de outliers;
- Matriz de correlação;
- Comparação entre pacientes diabéticos e não diabéticos.

## Pré-processamento

- Identificação de valores inconsistentes;
- Conversão de zeros para valores ausentes (NaN);
- Imputação utilizando a mediana;
- Nova análise exploratória após o tratamento;
- Separação entre variáveis preditoras e variável alvo;
- Divisão estratificada em treino e teste;
- Construção de Pipeline de Machine Learning.

## Modelagem

- Regressão Logística;
- Árvore de Decisão;
- Random Forest.

## Avaliação

- Accuracy;
- Precision;
- Recall;
- F1-score;
- ROC-AUC;
- Matriz de Confusão;
- Curva ROC;
- Validação Cruzada;
- Feature Importance.

## Discussão

- Comparação entre os modelos;
- Justificativa para escolha do modelo final;
- Discussão crítica dos resultados;
- Limitações do estudo;
- Trabalhos futuros.

---

# 🛠 Tecnologias Utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- KaggleHub
- Jupyter Notebook / Google Colab
- Git e GitHub

---

# 🤖 Modelos Avaliados

Durante o desenvolvimento foram comparados três algoritmos supervisionados de classificação:

| Modelo | Objetivo |
|---------|----------|
| Regressão Logística | Modelo linear utilizado como baseline |
| Árvore de Decisão | Modelo baseado em regras de decisão |
| Random Forest | Ensemble de Árvores de Decisão com agregação por votação |

A escolha do modelo final foi baseada na comparação entre diferentes métricas de desempenho, considerando principalmente o contexto de apoio ao diagnóstico médico.


---

# 📈 Comparação dos Modelos

Foram avaliados três algoritmos supervisionados de classificação para identificar pacientes com diabetes.

A comparação foi realizada utilizando as métricas **Accuracy**, **Precision**, **Recall**, **F1-score** e **ROC-AUC**, permitindo avaliar diferentes aspectos do desempenho dos modelos.

| Modelo | Accuracy | Precision | Recall | F1-score | ROC-AUC |
|---------|---------:|----------:|-------:|---------:|--------:|
| Regressão Logística | 70,78% | 60,00% | 50,00% | 54,55% | 81,30% |
| Árvore de Decisão | **78,57%** | **69,81%** | 68,52% | **69,16%** | 78,87% |
| Random Forest | 73,38% | 60,00% | **72,22%** | 65,55% | **82,31%** |

Observa-se que nenhum modelo apresentou desempenho superior em todas as métricas avaliadas.

A Árvore de Decisão obteve maior Accuracy, Precision e F1-score, enquanto o Random Forest apresentou maior Recall e ROC-AUC.

Como o objetivo deste projeto está relacionado ao apoio ao diagnóstico médico, a escolha do modelo priorizou a redução de falsos negativos, tornando o **Random Forest** a alternativa mais adequada.

---

# 🏆 Modelo Selecionado

O **Random Forest** foi escolhido como modelo final do projeto.

Embora a Árvore de Decisão tenha apresentado melhor Accuracy, Precision e F1-score, o Random Forest apresentou:

- maior Recall;
- maior ROC-AUC;
- melhor capacidade de identificar pacientes com diabetes;
- maior capacidade discriminativa entre as classes.

Em aplicações médicas, reduzir falsos negativos é mais importante do que maximizar apenas a Accuracy, justificando tecnicamente essa escolha.

---

# 📊 Principais Resultados

## Desempenho do Random Forest

| Métrica | Resultado |
|---------|----------:|
| Accuracy | **73,38%** |
| Precision | **60,00%** |
| Recall | **72,22%** |
| F1-score | **65,55%** |
| ROC-AUC | **82,31%** |

## Validação Cruzada

Para avaliar a capacidade de generalização do modelo, foi realizada validação cruzada estratificada.

| Métrica | Média |
|---------|-------:|
| Accuracy | **75,90%** |
| Precision | **63,71%** |
| Recall | **73,52%** |
| F1-score | **68,11%** |
| ROC-AUC | **83,48%** |

Os resultados demonstraram comportamento consistente entre diferentes divisões dos dados, indicando boa estabilidade do modelo.

---

# 📂 Estrutura do Repositório

```text
fiap-pos-ia-tech-challenge-fase-1/

├── 01_Desafio_FIAP_IA.ipynb
├── Relatório Técnico Final Tech Challenge – Fase 1.pdf
├── README.md
├── requirements.txt
├── Dockerfile
└── .gitignore
```

---

# 🚀 Como Executar

## 1. Clonar o repositório

```bash
git clone https://github.com/SEU-USUARIO/fiap-pos-ia-tech-challenge-fase-1.git
```

## 2. Acessar o diretório

```bash
cd fiap-pos-ia-tech-challenge-fase-1
```

## 3. Instalar as dependências

```bash
pip install -r requirements.txt
```

## 4. Executar o notebook

Abra o Jupyter Notebook ou Google Colab e execute:

```
01_Desafio_FIAP_IA.ipynb
```

Executando as células em sequência será possível reproduzir todas as etapas do projeto.

---

# 📄 Relatório Técnico

O relatório técnico completo encontra-se disponível no Google Docs.

📑 **Relatório Técnico**

https://docs.google.com/document/d/10BqKpLWb66796jTXiwen5AiUDzdpMsm3QuAoaxEK_y4/edit?usp=sharing

O documento apresenta detalhadamente:

- descrição do problema;
- metodologia utilizada;
- análise exploratória dos dados;
- pré-processamento;
- modelagem;
- avaliação dos modelos;
- discussão crítica dos resultados;
- limitações do estudo;
- conclusões.

---

# 💡 Principais Descobertas

Durante o desenvolvimento do projeto foram observados diversos aspectos relevantes:

- presença de valores iguais a zero em variáveis fisiológicas, representando dados ausentes;
- necessidade de tratamento dos dados antes da modelagem;
- Glucose foi a variável mais importante para as previsões;
- BMI, Age e Insulin também apresentaram elevada relevância para o modelo;
- a utilização de Pipeline reduziu o risco de Data Leakage;
- avaliar apenas a Accuracy mostrou-se insuficiente para um problema de diagnóstico médico;
- o Recall foi determinante para a escolha do modelo final.

---

# ⚠️ Limitações

Este estudo apresenta algumas limitações importantes.

- conjunto de dados relativamente pequeno (768 registros);
- dados provenientes de uma população específica;
- presença de valores ausentes tratados por imputação;
- ausência de validação utilizando bases externas;
- inexistência de dados clínicos adicionais que poderiam melhorar o desempenho dos modelos.

Dessa forma, o modelo deve ser interpretado como ferramenta de apoio à decisão clínica, não substituindo a avaliação realizada por profissionais da saúde.

---

# 🚀 Trabalhos Futuros

Como evolução deste projeto, podem ser desenvolvidas diversas melhorias, entre elas:

- otimização de hiperparâmetros;
- utilização de SHAP para interpretabilidade;
- comparação com algoritmos como XGBoost e LightGBM;
- validação utilizando bases externas;
- desenvolvimento de API para integração com sistemas hospitalares;
- monitoramento do desempenho do modelo em produção;
- avaliação do impacto do ajuste do threshold na redução de falsos negativos.

---

# 📚 Referências

- FIAP – Pós-Graduação em Inteligência Artificial.
- Pima Indians Diabetes Dataset.
- Pedregosa, F. et al. *Scikit-Learn: Machine Learning in Python*. Journal of Machine Learning Research.
- Documentação oficial do Pandas.
- Documentação oficial do NumPy.
- Documentação oficial do Matplotlib.
- Documentação oficial do Seaborn.

---

# 👩‍💻 Autora

**Natalia da Costa Silva**

Desenvolvedora Front-end e estudante da Pós-Graduação em Inteligência Artificial pela FIAP.

Este projeto foi desenvolvido como parte do **Tech Challenge – Fase 1**, aplicando conceitos de Ciência de Dados, Engenharia de Machine Learning e Inteligência Artificial para construção de uma solução de apoio ao diagnóstico clínico.

---

# 📜 Licença

Este projeto foi desenvolvido exclusivamente para fins acadêmicos como parte do **Tech Challenge – Fase 1** da Pós-Graduação em Inteligência Artificial da FIAP.

Os dados utilizados pertencem ao conjunto **Pima Indians Diabetes Dataset**, amplamente empregado para fins educacionais e de pesquisa científica.
