# 📊 TelecomX - Análise de Churn

Este projeto tem como objetivo analisar a evasão de clientes (**churn**) em uma empresa de telecomunicações, utilizando técnicas de **ETL**, **Análise Exploratória de Dados (EDA)** e **Modelagem Preditiva**.

---

## 🚀 Estrutura do Projeto
telecomx-churn/
├── data/
│    └── dados_tratados.csv          # Dados limpos e tratados
├── notebooks/
│    └── telecomx_churn_parte2.ipynb        # Notebook principal (Google Colab)
├── reports/
│    ├── resultados_modelos.txt      # Métricas dos modelos
│    ├── relatorio_final.md          # Insights e recomendações
│    └── grafico_churn.png           # Visualizações
└── README.md                        # Documentação do projeto


---

## 📥 Como Executar no Google Colab

1. Abra o [Google Colab](https://colab.research.google.com/).
2. Carregue o notebook `telecomx_churn_parte2.ipynb` da pasta `notebooks/`.
3. Execute célula por célula:
   - **ETL**: Carregamento e transformação dos dados.
   - **EDA**: Visualizações e estatísticas descritivas.
   - **Modelagem**: Treinamento e avaliação dos modelos.
   - **Relatório**: Geração de insights e recomendações.
4. Os arquivos gerados (dados tratados, relatórios e gráficos) podem ser baixados e organizados nas pastas `data/` e `reports/`.

---

## 📊 Resultados Obtidos

- **Modelos treinados**:
  - Regressão Logística → Acurácia ~86%
  - Random Forest → Acurácia ~89%

- **Variáveis mais importantes**:
  - Tempo de contrato (`tenure`)
  - Total de gastos (`TotalCharges`)
  - Gastos mensais (`MonthlyCharges`)
  - Tipo de contrato
  - Método de pagamento

---

## 🔎 Principais Insights

- Clientes com **contratos mensais** têm maior probabilidade de churn.
- **Tempo de contrato baixo** aumenta risco de evasão.
- **Gastos mensais altos** estão associados ao churn.
- Pagamentos via **Electronic check** aparecem como fator de risco.
- Serviços adicionais (backup, suporte técnico, proteção) reduzem evasão.

---

## 💡 Recomendações

- Criar campanhas de engajamento nos primeiros meses.
- Incentivar contratos anuais/bienais com descontos.
- Oferecer bônus de fidelidade.
- Monitorar clientes com alto risco (contrato mensal + pagamento eletrônico).

---

## 🛠️ Tecnologias Utilizadas

- **Python** (pandas, numpy, seaborn, matplotlib, scikit-learn, imbalanced-learn)
- **Google Colab** para execução
- **GitHub** para versionamento e compartilhamento

---

## 📌 Autor
Projeto desenvolvido por Gustavo Oliveira como parte de estudo de Data Science.

