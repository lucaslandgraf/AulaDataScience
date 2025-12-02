# 📊 Repositório de Data Science

Este repositório contém os materiais e projetos desenvolvidos para a disciplina de **Data Science**, com foco na aplicação de conceitos teóricos e práticos utilizando a linguagem **Python** no ambiente **Google Colab**.

## 🚀 Visão Geral do Projeto

O objetivo deste repositório é documentar o aprendizado e os exercícios práticos realizados ao longo do curso.

**Metodologia:**
*   **Conceitos Teóricos:** Fundamentos de estatística, aprendizado de máquina e governança de dados.
*   **Prática:** Implementação de algoritmos e análises em Python, utilizando o Google Colab como principal ferramenta.

> **Nota:** O planejamento original das aulas pode não corresponder exatamente aos tópicos abordados em cada encontro, devido à natureza dinâmica das aulas práticas.

## 📚 Conteúdo Programático e Aulas

A tabela a seguir resume o conteúdo teórico e prático abordado ao longo dos dois bimestres.

| Bimestre | Data | Aula | Conteúdo Principal |
| :---: | :---: | :---: | :--- |
| **1º Bimestre** | 29/Jul | Aula 01 | Governança de dados e LGPD |
| | 05/Aug | Aula 02 | Amostragem e Normalidade Amostral |
| | 12/Aug | Aula 03 | Estatística Descritiva: Média, Mediana, Variância, Desvio Padrão e Visualização de Dados (Distribuição de Frequências e Normal) |
| | 19/Aug | Aula 04 | Análise de Quartis, Regra de Sturges e Gráficos de Dispersão |
| | 26/Aug | Aula 05 | Testes de Hipótese Paramétricos e Gráficos de Plot |
| | 16/Sep | - | Correlação de Pearson e Covariância |
| | 23/Sep | - | Regressões Lineares e Não Lineares |
| | 30/Sep | Aula 07 | Qualidade dos Dados, Normalização e Preenchimento. Atividades Práticas em Bases de Dados Públicas/Abertas |
| **2º Bimestre** | 07/Oct | Aula 08 | Aprendizado de Máquina Não Supervisionado (K-Means, Expectation Maximization, Clusters Hierárquicos) |
| | 14/Oct | Aula 09 | Aprendizado de Máquina Supervisionado |
| | 21/Oct | Aula 10 | Regressão Logística, Árvores de Decisão e Random Forests |
| | 28/Oct | Aula 11 | Métricas para Avaliação de Modelos / Validação Cruzada |

## 💻 Projetos Práticos (Google Colab Notebooks)

Os principais tópicos práticos abordados nas aulas estão representados nos seguintes notebooks:

| Tópico | Notebook (Exemplo de Nome) | Descrição | Bibliotecas Chave |
| :--- | :--- | :--- | :--- |
| **Amostragem** | `Aula_120825.ipynb` | Demonstração de como criar uma população e extrair uma amostra aleatória simples em Python. | `random` |
| **Estatística Descritiva** | `Aula_120825.ipynb` | Cálculo de Média, Mediana, Moda, Variância, Desvio Padrão e Amplitude. | `statistics` |
| **Análise de Quartis e Outliers** | `Aula_020925.ipynb` | Cálculo de Q1, Q2, Q3, Intervalo Interquartil (IQR) e identificação de possíveis *outliers* com BoxPlot. | `numpy`, `matplotlib.pyplot` |
| **Distribuição Normal** | `Aula_04.ipynb` / `Aula_270825.ipynb` | Geração de dados com distribuição normal e visualização através de histogramas e curvas de densidade. | `numpy`, `matplotlib.pyplot` |
| **Testes de Hipótese** | `Aula_160925.ipynb` | Aplicação de Teste T para duas amostras independentes para verificar diferenças significativas. | `scipy.stats` |
| **Correlação** | `Aula_071025.ipynb` | Cálculo de correlação entre variáveis e visualização com *Heatmap* (usando o dataset do Titanic como exemplo). | `pandas`, `seaborn` |
| **Regressão Linear** | `Aula_211025.ipynb` | Implementação de Regressão Linear Simples, cálculo de coeficientes ($\alpha$ e $\beta$), $R^2$ e visualização da reta de regressão. | `numpy`, `pandas`, `matplotlib.pyplot` |
| **K-Means (Clustering)** | `Aula_111125.ipynb` | Aplicação do algoritmo K-Means para segmentação de clientes com base em Renda e Gasto Mensal. | `numpy`, `pandas`, `sklearn.cluster` |

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python
*   **Ambiente:** Google Colab
*   **Bibliotecas Principais:**
    *   `numpy`: Para operações numéricas e vetoriais.
    *   `pandas`: Para manipulação e análise de dados.
    *   `matplotlib` e `seaborn`: Para visualização de dados.
    *   `scipy`: Para testes estatísticos.
    *   `scikit-learn (sklearn)`: Para algoritmos de Machine Learning.
    *   `random` e `statistics`: Para funções estatísticas básicas e amostragem.

## 🔗 Links dos Notebooks (Exemplo)

Os links originais dos notebooks no Google Drive/Colab foram extraídos do conteúdo. Você pode usá-los para acessar os arquivos:

*   **Aula 02/09/25 (Quartis/Outliers):** `https://colab.research.google.com/drive/1PFHCyhvUdakebcdQTmjswGSK3YdrzCsX`
*   **Aula 07/10/25 (Correlação/Heatmap):** `https://colab.research.google.com/drive/1kJJo8qv9zXSKDBD0GrxNTmiAFh8POWgm`
*   **Aula 11/11/25 (K-Means):** `https://colab.research.google.com/drive/15Fvpn9_crKX70qLuomFapdxoFMDpKcxH`
*   **Aula 12/08/25 (Amostragem/Estatística Descritiva):** `https://colab.research.google.com/drive/1CDzNCLtl6DGSxiAs_kg2nrv6fbIChL6O`
*   **Aula 16/09/25 (Teste de Hipótese):** `https://colab.research.google.com/drive/17MA7BeCOmDJNViN_DqYNepW5GJ_jTnXT`
*   **Aula 21/10/25 (Regressão Linear):** `https://colab.research.google.com/drive/19dM4pZY3kQZs_SGywPS76TUM9MkHqH5w`
*   **Aula 27/08/25 (Distribuição Normal):** `https://colab.research.google.com/drive/1LE_PRerx_qdBctn34-yrShTg2-MpRSNT`
*   **Aula 04 (Distribuição Normal):** `https://colab.research.google.com/drive/1ZtCKRcKf3iq3jph3-GqygCz6fSM9k_73`

