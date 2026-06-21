# 📊 Análise de Preço Médio por Categoria - Market API

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org)
[![Pandas](https://img.shields.io/badge/Pandas-2.0+-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5+-11557C?style=for-the-badge&logo=python&logoColor=white)](https://matplotlib.org)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.12+-4C72B0?style=for-the-badge&logo=python&logoColor=white)](https://seaborn.pydata.org)

## 🎯 Sobre o Projeto
Este projeto foi desenvolvido para automatizar a extração, tratamento e visualização de dados de produtos de um e-commerce. A partir dos dados brutos de uma API, foi realizada uma análise para identificar o **preço médio dos produtos por departamento**, gerando um relatório executivo limpo e um gráfico de alta qualidade para tomada de decisão.

---

## 📈 Resultado Visual
O gráfico final foi estilizado utilizando a paleta `mako` do Seaborn, com rótulos de dados dinâmicos formatados em moeda aplicados diretamente via Matplotlib:

![Gráfico de Preço Médio](./grafico_preco_medio.png)
---

## 🛠️ O que foi feito? (Etapas do Projeto)

* **Extração:** Conexão com API para coleta dos dados de produtos.
* **Tratamento de Dados (Pandas):** Limpeza de strings, tratamento de valores nulos e estruturação da tabela.
* **Análise e Agrupamento:** Filtragem avançada e agrupamento (`groupby`) para calcular as médias reais de cada categoria.
* **Visualização Avançada (Matplotlib + Seaborn):** Criação de um gráfico de barras moderno com laço de repetição (`for`) automatizado usando Matplotlib para a inserção das etiquetas de preço e salvamento da imagem em alta definição.
* **Exportação:** Geração de um arquivo `relatorio_preco_medio.csv` pronto para consumo em ferramentas de BI.

---

## 💻 Como Rodar o Projeto

1. Clone o repositório:
```bash
git clone [https://github.com/SEU_USUARIO/project_market.git](https://github.com/SEU_USUARIO/project_market.git)
