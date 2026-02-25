### 📊 Telecom X – Análise de Evasão (Churn)

### 🎯 Objetivo da Análise

Este projeto tem como objetivo analisar os dados da empresa Telecom X e entender os fatores associados à evasão de clientes (Churn).

A proposta foi aplicar o processo de ETL (Extração, Transformação e Carga) utilizando Python e, em seguida, realizar uma análise exploratória de dados (EDA) para identificar padrões associados ao cancelamento de clientes.

### 🔎 Principais Insights

Durante a análise, foram identificados alguns padrões importantes:

- Clientes com contrato mensal apresentam maior taxa de evasão.

- O método de pagamento Electronic check está associado a maior churn.

- Clientes com serviço de fibra óptica apresentam maior índice de cancelamento.

- A evasão ocorre principalmente nos primeiros meses de contrato.

Esses fatores indicam que o nível de vínculo do cliente com a empresa influencia diretamente a probabilidade de cancelamento.

### 🗂 Estrutura do Projeto

O projeto é organizado em um único notebook, onde toda a análise acontece:

```
Challenge_TelecomX/
|
├── TelecomX_BR.ipynb      -> Notebook principal com ETL, gráficos e análises
├── TelecomX_dicionario.md -> Dicionário de dados
├── README.md              -> Documentação do projeto
```

No notebook, o conteúdo está organizado da seguinte forma:

* Importação das bibliotecas
* Leitura dos dados
* Análise Exploratória dos dados
* Criação de gráficos
* Análises escritas
* Conclusão e Insights
* Recomendações finais

---

### 🛠 Tecnologias Utilizadas

- Python

- Pandas

- Matplotlib

- Google Colab

### ▶ Como Executar

1. Baixe ou clone este repositório:
```bash
git clone https://github.com/marceloBaumgratz/Challenge_TelecomX
```
2. Abra o arquivo **TelecomX_BR.ipynb** no Google Colab ou Jupyter Notebook.
3. Execute as células.
---
### 📚 Observação Final
#### Projeto desenvolvido no Google Colab como parte do curso de Análise de Dados da Alura, com foco na prática de ETL e interpretação de resultados.
---
