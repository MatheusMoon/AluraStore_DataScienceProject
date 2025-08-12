# 📊 AluraStore - Data Science Project

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.x-green.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-orange.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-red.svg)
![Status](https://img.shields.io/badge/Status-Concluído-success.svg)

Este projeto realiza uma **análise comparativa de desempenho** entre quatro lojas virtuais da **AluraStore**, utilizando dados de vendas, avaliações de clientes e custos de frete.  
O objetivo é identificar padrões, oportunidades e problemas, a fim de apoiar a **decisão de vender a loja com pior desempenho**.

---

## 🎯 Propósito da Análise
O estudo visa responder à seguinte questão de negócio:  
> "Qual das quatro lojas apresenta pior desempenho e deve ser vendida?"

Para isso, foram avaliados:
- **Faturamento total**
- **Distribuição de vendas por categoria**
- **Média de avaliações dos clientes**
- **Produtos mais e menos vendidos**
- **Frete médio**

---

## 📂 Estrutura do Projeto

```plaintext
AluraStore_DataScienceProject/
│
├── 📄 README.md                     # Documentação do projeto
├── 📓 AluraStore_DataScienceProject.ipynb  # Notebook com a análise completa
├── 📁 dados/                         # (Opcional) Pasta para salvar dados CSV localmente
│   ├── loja_1.csv
│   ├── loja_2.csv
│   ├── loja_3.csv
│   └── loja_4.csv
└── 📁 imagens/                       # (Opcional) Gráficos exportados para o README
```
---

# 📊 Exemplos de Gráficos e Insights Obtidos

Faturamento por Loja
📌 Insight: Loja 4 possui o menor faturamento.

Distribuição de Categorias
📌 Insight: "A categoria Móveis é a mais vendida em todas as lojas."

Média de Avaliação
📌 Insight: Loja 4 tem a segunda pior nota média (4.0).

Frete Médio por Loja
📌 Insight: Mesmo com o menor frete médio, a Loja 4 não teve bom desempenho.

---

#💡 Principais Conclusões

Loja 4 apresentou:

Menor faturamento

Segunda pior avaliação

Menor frete médio, sem impacto positivo nas vendas

Recomendação: vender a Loja 4

---

▶️ Instruções para Executar o Notebook
Clonar o repositório:

bash
Copiar
Editar
git clone https://github.com/usuario/AluraStore_DataScienceProject.git
cd AluraStore_DataScienceProject
Instalar as dependências:
É recomendado o uso de um ambiente virtual.

bash
Copiar
Editar
pip install pandas matplotlib
Executar o notebook:

Abra com Jupyter Notebook ou JupyterLab:

bash
Copiar
Editar
jupyter notebook AluraStore_DataScienceProject.ipynb
Ou execute direto no Google Colab (subindo o arquivo .ipynb).

---

# 📌 Tecnologias Utilizadas
Python 3

Pandas → Manipulação e análise de dados

Matplotlib → Visualização gráfica

Jupyter Notebook → Ambiente de desenvolvimento interativo

---
✍️ Autor: Matheus Cordeiro
📅 Data: 08/2025
