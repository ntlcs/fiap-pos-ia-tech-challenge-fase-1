# fiap-pos-ia-tech-challenge-fase-1
fiap-pos-ia-tech-challenge-fase-1

# 🏥 Tech Challenge – Fase 1 | Sistema Inteligente de Apoio ao Diagnóstico de Diabetes

> Projeto desenvolvido para o **Tech Challenge – Fase 1** da Pós-Graduação em Inteligência Artificial da **FIAP**, aplicando técnicas de Ciência de Dados e Machine Learning para apoio ao diagnóstico clínico.

---

# 📖 Sobre o Projeto

O crescimento do volume de exames e prontuários eletrônicos torna cada vez mais importante o uso de sistemas inteligentes capazes de auxiliar profissionais da saúde na tomada de decisão.

Neste contexto, este projeto desenvolve uma solução de **Machine Learning** para apoiar a identificação de pacientes com possível diabetes a partir de informações clínicas estruturadas.

Todo o desenvolvimento segue um fluxo completo de Ciência de Dados, desde a compreensão do problema até a avaliação crítica dos modelos treinados.

---

# 🎯 Objetivos

O projeto possui os seguintes objetivos:

- Compreender o problema de negócio proposto pela FIAP;
- Realizar uma Análise Exploratória de Dados (EDA);
- Avaliar a qualidade do conjunto de dados;
- Identificar inconsistências e valores inválidos;
- Realizar o pré-processamento dos dados;
- Construir um Pipeline de Machine Learning;
- Treinar e comparar diferentes algoritmos de classificação;
- Avaliar os modelos utilizando métricas adequadas ao contexto médico;
- Interpretar os resultados obtidos;
- Discutir limitações e possibilidades de evolução do projeto.

---

# 🩺 Dataset

Foi utilizado o **Pima Indians Diabetes Dataset**, amplamente empregado em pesquisas e estudos sobre classificação de diabetes.

### Características

| Item | Valor |
|------|------:|
| Registros | 768 |
| Variáveis | 9 |
| Tipo do problema | Classificação Binária |

### Variáveis

| Variável | Descrição |
|----------|-----------|
| Pregnancies | Número de gestações |
| Glucose | Concentração de glicose |
| BloodPressure | Pressão arterial |
| SkinThickness | Espessura da dobra cutânea |
| Insulin | Nível de insulina |
| BMI | Índice de Massa Corporal |
| DiabetesPedigreeFunction | Histórico familiar |
| Age | Idade |
| Outcome | Diagnóstico (0 = Não diabético / 1 = Diabético) |

---

# 🔬 Metodologia

O projeto foi desenvolvido seguindo o processo **CRISP-DM**, composto pelas seguintes etapas:

- Entendimento do problema
- Entendimento dos dados
- Preparação dos dados
- Modelagem
- Avaliação

Durante o desenvolvimento foram aplicadas boas práticas de Ciência de Dados, incluindo:

- análise exploratória dos dados;
- identificação de inconsistências;
- tratamento de valores iguais a zero;
- imputação utilizando Pipeline;
- prevenção de Data Leakage;
- divisão estratificada entre treino e teste;
- validação cruzada;
- comparação entre diferentes algoritmos.

---

# 📊 Etapas Desenvolvidas

O notebook contempla:

- ✅ Entendimento do problema
- ✅ Carregamento e inspeção dos dados
- ✅ Estatística descritiva
- ✅ Análise Exploratória (EDA)
- ✅ Identificação de valores inconsistentes
- ✅ Tratamento dos dados
- ✅ Nova EDA após tratamento
- ✅ Pipeline de pré-processamento
- ✅ Treinamento dos modelos
- ✅ Avaliação das métricas
- ✅ Comparação entre modelos
- ✅ Validação Cruzada
- ✅ Feature Importance
- ✅ Discussão crítica
- ✅ Limitações do estudo
- ✅ Conclusão

---

# 🤖 Modelos Avaliados

Foram treinados três algoritmos supervisionados:

- Regressão Logística
- Árvore de Decisão
- Random Forest

---

# 📈 Resultados

O **Random Forest** apresentou o melhor equilíbrio entre desempenho e capacidade discriminativa.

### Métricas obtidas

| Métrica | Valor |
|---------|------:|
| Accuracy | **73,38%** |
| Precision | **60,00%** |
| Recall | **72,22%** |
| F1-score | **65,55%** |
| ROC-AUC | **82,31%** |

### Validação Cruzada

| Métrica | Média |
|---------|------:|
| Accuracy | **75,90%** |
| Precision | **63,71%** |
| Recall | **73,52%** |
| F1-score | **68,11%** |
| ROC-AUC | **83,48%** |

Como o problema está relacionado ao apoio ao diagnóstico médico, a métrica de maior interesse foi o **Recall**, pois reduz a probabilidade de pacientes com diabetes serem classificados incorretamente como saudáveis.

---

# 📌 Principais Descobertas

Durante a análise foram identificados diversos pontos relevantes:

- presença de valores iguais a zero em variáveis fisiológicas;
- necessidade de imputação dos dados;
- forte influência da variável **Glucose** na classificação;
- importância de variáveis como BMI, Age e DiabetesPedigreeFunction;
- necessidade de avaliar o modelo além da Accuracy.

---

# 🛠 Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- KaggleHub
- Jupyter Notebook

---

# 📁 Estrutura do Projeto

```text
fiap-pos-ia-tech-challenge-fase-1/

├── 01_Desafio_FIAP_IA.ipynb
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

## 2. Acessar a pasta

```bash
cd fiap-pos-ia-tech-challenge-fase-1
```

## 3. Instalar as dependências

```bash
pip install -r requirements.txt
```

## 4. Executar o notebook

Abra o Jupyter Notebook ou Google Colab e execute o arquivo:

```
01_Desafio_FIAP_IA.ipynb
```

---


# 📄 Relatório Técnico

O relatório técnico completo do projeto, contendo a descrição da metodologia, análise exploratória dos dados, pré-processamento, modelagem, avaliação dos modelos e discussão dos resultados, está disponível no link abaixo:

📑 **Relatório Técnico (Google Docs)**

https://docs.google.com/document/d/1vsQCHuIZOjnCy9FgVbveiFuwZtxRZ2qMP6IjLLLNvuo/edit?usp=sharing

> Recomenda-se acessar o documento utilizando uma conta Google para visualizar a versão mais atualizada.

---

# ⚠️ Limitações

Este estudo apresenta algumas limitações:

- conjunto de dados relativamente pequeno;
- dados provenientes de uma população específica;
- presença de dados ausentes tratados por imputação;
- ausência de validação em bases externas.

Portanto, o modelo deve ser interpretado como ferramenta de apoio à decisão clínica e não como substituto da avaliação médica.

---

# 🚀 Trabalhos Futuros

Como evolução deste projeto, podem ser desenvolvidas as seguintes melhorias:

- otimização de hiperparâmetros;
- utilização de SHAP para interpretabilidade;
- avaliação de novos algoritmos (XGBoost e LightGBM);
- validação em bases externas;
- desenvolvimento de API para integração com sistemas hospitalares;
- monitoramento do modelo em produção.

---

# 📚 Referências

- FIAP – Pós-Graduação em Inteligência Artificial
- Pima Indians Diabetes Dataset
- Pandas Documentation
- Scikit-Learn Documentation
- Seaborn Documentation
- Matplotlib Documentation

---

# 👩‍💻 Autora

**Natalia da Costa Silva**

Projeto desenvolvido como parte do **Tech Challenge – Fase 1** da Pós-Graduação em Inteligência Artificial da **FIAP**, aplicando técnicas de Ciência de Dados, Engenharia de Machine Learning e Inteligência Artificial para apoio ao diagnóstico clínico.
