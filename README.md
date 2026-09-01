# CancelamentoCartao
Estudo em Python para identificar o motivo dos clientes cancelarem o Cartão de Crédito


# 💳 Análise de Cancelamento de Cartão de Crédito

Projeto de **Análise de Dados com Python** desenvolvido com o objetivo de identificar os principais fatores relacionados ao **cancelamento de cartões de crédito pelos clientes**.

A análise busca transformar os dados dos clientes em informações que possam auxiliar na identificação de padrões de comportamento e na tomada de decisões para **reduzir a taxa de cancelamento (churn)**.

---

## 🎯 Objetivo

Identificar características e comportamentos dos clientes que apresentam maior propensão ao cancelamento do cartão de crédito.

Entre os pontos analisados estão:

* Perfil dos clientes que cancelaram o cartão;
* Relação entre idade e cancelamento;
* Tempo de relacionamento com o banco;
* Limite e utilização do cartão;
* Número de produtos contratados;
* Frequência de utilização do cartão;
* Categoria e perfil dos clientes;
* Comparação entre clientes ativos e clientes que cancelaram.

---

## 🛠️ Tecnologias utilizadas

* **Python**
* **Pandas** — manipulação e tratamento dos dados
* **NumPy** — operações e análise numérica
* **Matplotlib** — visualização de dados
* **Seaborn** — criação de gráficos estatísticos
* **Jupyter Notebook** — desenvolvimento da análise

---

## 📂 Estrutura do projeto

```text
CancelamentoCartao/
│
├── Analise.ipynb
├── ClientesBanco.csv
├── README.md
└── .gitignore
```

### Arquivos

**Analise.ipynb**

Notebook contendo todo o processo de análise, incluindo:

* Importação dos dados;
* Exploração inicial;
* Tratamento e limpeza;
* Análise estatística;
* Criação de visualizações;
* Identificação de padrões;
* Conclusões.

**ClientesBanco.csv**

Dataset utilizado como fonte dos dados para a análise.

---

## 🔎 Etapas da análise

### 1. Importação dos dados

Os dados foram carregados utilizando a biblioteca Pandas.

```python
import pandas as pd

tabela = pd.read_csv("ClientesBanco.csv")
```

### 2. Exploração dos dados

Foram realizadas análises iniciais para compreender:

* Quantidade de registros;
* Quantidade de colunas;
* Tipos de dados;
* Valores ausentes;
* Distribuição das informações.

### 3. Tratamento dos dados

Foi realizada a preparação da base para a análise, incluindo:

* Identificação de valores nulos;
* Remoção de informações desnecessárias;
* Ajustes nos tipos de dados;
* Tratamento das variáveis utilizadas na análise.

### 4. Análise exploratória

Foram realizadas comparações entre clientes que **permaneceram** e clientes que **cancelaram** o cartão.

As análises procuram responder perguntas como:

> Quais características são mais comuns entre os clientes que cancelam o cartão?

> Existe relação entre utilização do cartão e cancelamento?

> Clientes com determinado perfil apresentam maior taxa de churn?

---

## 📊 Principais insights

A análise permite identificar padrões relacionados ao comportamento dos clientes e entender quais características apresentam maior relação com o cancelamento.

Esses insights podem ser utilizados para:

* Identificar clientes com maior risco de churn;
* Criar estratégias de retenção;
* Melhorar a experiência dos clientes;
* Desenvolver campanhas direcionadas;
* Apoiar decisões estratégicas baseadas em dados.

> **Observação:** os insights e conclusões detalhadas podem ser encontrados no notebook `Analise.ipynb`.

---

## 📈 Resultado

O projeto demonstra na prática a utilização de **Python e Pandas para Análise Exploratória de Dados**, passando desde a preparação da base até a identificação de padrões relevantes.

O objetivo principal é transformar uma base de dados de clientes em **informações úteis para apoiar decisões de negócio**.

---

## 🚀 Como executar o projeto

### 1. Clone o repositório

```bash
git clone https://github.com/lucasssilveira/CancelamentoCartao.git
```

### 2. Acesse a pasta

```bash
cd CancelamentoCartao
```

### 3. Instale as bibliotecas necessárias

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Execute o Jupyter Notebook

```bash
jupyter notebook
```

Depois, abra o arquivo:

```text
Analise.ipynb
```

---

## 👨‍💻 Autor

**Lucas Silveira**

Projeto desenvolvido como parte dos estudos em **Análise de Dados com Python, Pandas e visualização de dados**.

---

⭐ Se este projeto foi útil para você, considere deixar uma estrela no repositório!
