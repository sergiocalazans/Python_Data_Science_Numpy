# Python Data Science Numpy

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![NumPy](https://img.shields.io/badge/NumPy-1.21+-blue.svg)

Este repositório apresenta um curso completo em formato de Jupyter Notebook sobre os fundamentos de Python aplicados à Ciência de Dados, com ênfase especial na biblioteca **NumPy** (Numerical Python). O material guia o usuário desde os conceitos básicos da linguagem até a manipulação avançada de arrays multidimensionais, que são a base para computação científica e análise de dados em Python.

## 📂 Estrutura do Projeto

```
.
├── Python_Data_Science_Numpy.ipynb  # Notebook principal com o curso
└── README.md           # Este arquivo
```

## 📖 Tabela de Conteúdos

1.  [**Introdução ao Python**](#1-introdução-ao-python)
    -   Configuração do ambiente (Anaconda, Google Colab)
    -   Primeiro contato com dados usando NumPy (`np.loadtxt`)
    -   Realizando a primeira operação vetorizada

2.  [**Características Básicas da Linguagem**](#2-características-básicas-da-linguagem)
    -   Operações matemáticas e expressões
    -   Variáveis, tipos de dados (`int`, `float`, `bool`, `str`, `None`)
    -   Conversão de tipos e formatação de strings (`f-strings`)

3.  [**Trabalhando com Listas**](#3-trabalhando-com-listas)
    -   Criação, seleção, fatiamento e concatenação
    -   Principais métodos (`.sort()`, `.append()`, `.pop()`, `.copy()`)

4.  [**Estruturas de Repetição e Condicionais**](#4-estruturas-de-repetição-e-condicionais)
    -   Laços `for` e loops aninhados
    -   List Comprehensions
    -   Estruturas `if`, `elif`, `else`

5.  [**NumPy Básico**](#5-numpy-básico)
    -   **Criação de Arrays**:
        -   A partir de listas Python (`np.array`)
        -   A partir de arquivos externos (`np.loadtxt`)
        -   Comparativo de desempenho: NumPy vs. Listas
    -   **Operações com Arrays**:
        -   Operações vetorizadas (array com escalar, array com array)
        -   Operações em arrays de duas dimensões
    -   **Seleção em Arrays**:
        -   Indexação e fatiamento (`slicing`)
        -   Indexação com arrays booleanos (filtros)
    -   **Atributos e Métodos**:
        -   Atributos: `.shape`, `.ndim`, `.size`, `.dtype`, `.T`
        -   Métodos: `.tolist()`, `.reshape()`, `.resize()`
    -   **Estatísticas com Arrays**:
        -   Cálculo de média (`np.mean`), desvio padrão (`np.std`) e soma (`np.sum`)
        -   Uso do parâmetro `axis` para operações em eixos específicos

---

## 🎯 Sobre o Notebook

O notebook `Python_Data_Science_Numpy.ipynb` é um guia prático e detalhado que cobre os seguintes tópicos:

### 4. Fundamentos do Python
As seções iniciais constroem uma base sólida em Python, cobrindo desde a sintaxe e tipos de dados até estruturas de controle como laços e condicionais. Estes são pré-requisitos essenciais para qualquer pessoa que queira trabalhar com Data Science.

### 5. NumPy Básico
Esta é a seção principal do notebook, onde você mergulhará no poder da computação numérica com NumPy. Os principais aprendizados incluem:
-   **Performance Superior**: Uma demonstração prática (`%timeit`) que prova por que os arrays NumPy são ordens de magnitude mais rápidos que as listas Python para operações numéricas.
-   **Criação e Manipulação de Arrays**: Aprenda a criar arrays multidimensionais a partir de diversas fontes e a inspecionar suas propriedades com atributos como `.shape`, `.ndim` e `.dtype`.
-   **Poder da Vetorização**: Entenda como realizar operações matemáticas complexas em arrays inteiros sem a necessidade de escrever laços `for` explícitos, resultando em um código mais limpo, legível e performático.
-   **Seleção de Dados Avançada**: Domine técnicas de fatiamento e indexação booleana para filtrar e selecionar dados de forma eficiente e intuitiva.
-   **Transformação de Dados**: Utilize métodos como `.reshape()` e `.T` (transposição) para moldar seus dados no formato necessário para análises e algoritmos de machine learning.
-   **Análise Estatística**: Calcule estatísticas descritivas fundamentais (média, desvio padrão, soma) de forma simples e eficiente, controlando o eixo da operação.

## 🚀 Como Executar

Para executar este notebook em sua máquina local, siga os passos abaixo.

### Pré-requisitos
-   Python 3.7 ou superior
-   Jupyter Notebook ou JupyterLab (geralmente incluído em distribuições como Anaconda)

### Passos
1.  Clone o repositório:
    ```bash
    git clone https://github.com/sergiocalazans/Python_Data_Science_Numpy.git
    ```

2.  Navegue até o diretório clonado:
    ```bash
    cd Python_Data_Science_Numpy
    ```

3.  Instale a biblioteca NumPy (se ainda não tiver):
    ```bash
    pip install numpy
    ```

4.  Inicie o Jupyter Notebook ou JupyterLab:
    ```bash
    jupyter notebook
    # ou
    jupyter lab
    ```
5.  Abra o arquivo `Python_Data_Science_Numpy.ipynb` e execute as células.

Alternativamente, você pode abrir o notebook diretamente no **Google Colab** clicando no badge abaixo, sem necessidade de instalação local.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Gunga-16/Python_Data_Science_Numpy/blob/main/Python_Data_Science_Numpy.ipynb)
