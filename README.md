# 📊 DIO – Detecção de Anomalias em Transações

<!--
  Este repositório contém o projeto desenvolvido durante o curso da DIO que tem como objetivo
  detectar anomalias em séries temporais de transações financeiras usando técnicas de Machine
  Learning. O trabalho inclui preparação de dados, modelagem, avaliação e visualização dos
  resultados.
-->

## 🎯 Objetivo do Projeto

- **Detectar** transações que se desviam significativamente do padrão normal.
- **Aplicar** métodos estatísticos e de aprendizado de máquina (Isolation Forest, Local Outlier Factor, etc.).
- **Visualizar** anomalias em gráficos interativos para facilitar a análise.

## 📂 Estrutura do Repositório

```
.
├── data/                # Conjunto de dados (CSV) usado nos exemplos
├── notebooks/           # Jupyter notebooks com experimentos e EDA
├── src/                 # Código-fonte Python (pipeline, modelos, utils)
│   ├── __init__.py
│   ├── data_loader.py
│   ├── preprocessing.py
│   ├── model.py
│   └── visualization.py
├── requirements.txt     # Dependências do projeto
├── README.md            # <‑‑ Este arquivo
└── LICENSE              # Licença open‑source (MIT)
```

## 🚀 Como Executar

1. **Criar e ativar o ambiente virtual**
   ```bash
   python -m venv .venv
   source .venv/bin/activate   # Linux/macOS
   .venv\Scripts\activate      # Windows
   ```
2. **Instalar as dependências**
   ```bash
   pip install -r requirements.txt
   ```
3. **Abrir os notebooks**
   ```bash
   jupyter notebook notebooks/
   ```
   O notebook principal `Anomaly_Detection.ipynb` contém todo o fluxo de trabalho.

## 🛠️ Tecnologias Utilizadas

- **Python 3.13**
- **pandas, numpy** – Manipulação de dados
- **scikit‑learn** – Algoritmos de detecção de anomalias
- **matplotlib, seaborn, plotly** – Visualizações interativas
- **Jupyter Notebook** – Ambiente exploratório

## 📊 Métricas de Avaliação

- **Precision / Recall** para identificar falsos positivos/negativos
- **ROC‑AUC** para avaliar a capacidade discriminativa dos modelos

## 📄 Licença

Este projeto está licenciado sob a licença MIT – sinta‑se à vontade para usar, modificar e distribuir.

---

*Projeto desenvolvido para fins educacionais durante o programa DIO – Data Science & Machine Learning.*
# Deteccao-de-anomalias-em-transacoes
