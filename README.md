# fiap-pos-ia-tech-challenge-fase-1
fiap-pos-ia-tech-challenge-fase-1

# 🏥 Tech Challenge – Fase 1 | IA para Suporte ao Diagnóstico Clínico

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-success)
![FIAP](https://img.shields.io/badge/FIAP-Tech%20Challenge-red)

---

## 📖 Sobre o Projeto

Este projeto foi desenvolvido como parte do **Tech Challenge – Fase 1** da Pós-Graduação em **Inteligência Artificial da FIAP**.

O desafio consiste em desenvolver a base de um sistema inteligente capaz de apoiar o diagnóstico clínico por meio da análise de dados utilizando técnicas de **Ciência de Dados**, **Machine Learning** e **Inteligência Artificial**.

Nesta primeira fase, o projeto está concentrado na realização de uma **Análise Exploratória de Dados (EDA)** sobre o **Pima Indians Diabetes Dataset**, buscando compreender a estrutura dos dados, avaliar sua qualidade e identificar padrões que servirão de base para as etapas de pré-processamento e modelagem.

---

# 🎯 Objetivos

- Realizar uma Análise Exploratória de Dados (EDA);
- Compreender a estrutura e qualidade do conjunto de dados;
- Identificar inconsistências e possíveis problemas nos dados;
- Analisar a distribuição das variáveis clínicas;
- Avaliar relações entre os atributos e o diagnóstico de diabetes;
- Preparar o dataset para as próximas etapas de Machine Learning.

---

# 🩺 Dataset

Foi utilizado o **Pima Indians Diabetes Dataset**, amplamente empregado em estudos de classificação na área da saúde.

### Características

- **768 registros**
- **9 variáveis**
- Problema de **Classificação Binária**

| Variável | Descrição |
|----------|-----------|
| Pregnancies | Número de gestações |
| Glucose | Concentração de glicose |
| BloodPressure | Pressão arterial |
| SkinThickness | Espessura da dobra cutânea |
| Insulin | Nível de insulina |
| BMI | Índice de Massa Corporal |
| DiabetesPedigreeFunction | Histórico familiar de diabetes |
| Age | Idade |
| Outcome | Diagnóstico (0 = Não diabético / 1 = Diabético) |

---

# 📊 Etapas Desenvolvidas

Atualmente o notebook contempla:

- ✔ Importação das bibliotecas
- ✔ Carregamento do dataset
- ✔ Exploração inicial dos dados
- ✔ Verificação dos tipos de dados
- ✔ Estatísticas descritivas
- ✔ Análise da integridade dos dados
- ✔ Distribuição da variável alvo
- ✔ Distribuição das variáveis
- ✔ Análise de assimetria
- ✔ Análise de curtose
- ✔ Detecção de outliers
- ✔ Correlação entre variáveis
- ✔ Correlação com a variável alvo
- ✔ Comparação entre pacientes diabéticos e não diabéticos
- ✔ Investigação de valores iguais a zero
- ✔ Conclusões da Análise Exploratória

---

# 🔬 Metodologia

O desenvolvimento segue a metodologia **CRISP-DM**, composta pelas etapas:

- Entendimento do problema
- Entendimento dos dados
- Preparação dos dados
- Modelagem
- Avaliação

Durante as próximas fases do projeto, serão desenvolvidos modelos supervisionados de classificação para apoio ao diagnóstico clínico.

Como se trata de um problema médico, será dada maior atenção ao **Recall**, buscando minimizar falsos negativos, que representam pacientes doentes classificados incorretamente como saudáveis.

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
tech-challenge-fiap/

│
├── notebooks/
│   └── EDA_Diabetes.ipynb
│
├── images/
│
├── requirements.txt
│
└── README.md
```

---

# 🚀 Como Executar

### 1. Clone este repositório

```bash
git clone https://github.com/seuusuario/tech-challenge-fiap.git
```

### 2. Acesse a pasta do projeto

```bash
cd tech-challenge-fiap
```

### 3. Instale as dependências

```bash
pip install -r requirements.txt
```

### 4. Abra o Jupyter Notebook

```bash
jupyter notebook
```

ou

```bash
jupyter lab
```

### 5. Execute o notebook

Abra o arquivo **EDA_Diabetes.ipynb** e execute as células sequencialmente para reproduzir toda a análise exploratória.

---

# 📈 Próximas Etapas

Após a conclusão da EDA, serão desenvolvidas as seguintes etapas:

- Pré-processamento dos dados
- Engenharia de atributos
- Construção do Pipeline de Machine Learning
- Treinamento dos modelos
- Avaliação utilizando métricas de classificação
- Interpretabilidade dos modelos com SHAP
- Comparação entre algoritmos
- Conclusões finais

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

**Natalia**

Projeto desenvolvido como parte do **Tech Challenge – Fase 1** da Pós-Graduação em Inteligência Artificial da FIAP, aplicando técnicas de Ciência de Dados e Machine Learning para suporte ao diagnóstico clínico.
