# 📌 Análise Avançada de Série Temporal

## 📖 Sobre o Projeto
Este projeto realiza uma **análise avançada** de uma série temporal contendo dados históricos, com o objetivo de:

- Entender a **tendência** dos valores ao longo do tempo.
- Prever os **valores futuros** usando modelos estatísticos.
- Identificar **picos** e **anomalias**.
- Detectar **padrões sazonais**.
- Gerar **gráficos interativos** e um **relatório Excel** completo.

---

## 🚀 Tecnologias Utilizadas
- **Python 3.11+**
- **Pandas** → manipulação e análise de dados
- **NumPy** → cálculos numéricos
- **Matplotlib / Seaborn** → visualizações
- **Scikit-learn** → regressão linear
- **Statsmodels** → modelo ARIMA
- **Prophet** → previsão avançada (opcional)
- **Plotly** → gráficos interativos (opcional)
- **Jupyter Notebook** → ambiente de desenvolvimento

---

## 🔹 Funcionalidades
✔️ Limpeza e preparação dos dados  
✔️ Estatísticas descritivas  
✔️ Análise de **tendência linear**  
✔️ Previsão de valores futuros com **ARIMA** e **Prophet**  
✔️ Detecção de **anomalias** usando **z-score**  
✔️ Análise de **sazonalidade** mensal/anual  
✔️ Geração automática de **gráficos**  
✔️ Exportação de **relatório Excel** com todas as análises

---

## 📂 Estrutura do Projeto
```bash
.
├── Untitled.ipynb           # Notebook com código principal
├── relatorio_final.xlsx     # Relatório Excel com resultados e gráficos
├── README.md               # Documentação do projeto
└── /plots                  # Pasta com gráficos gerados
```

---

## ⚙️ Instalação
```bash
# Criar ambiente virtual (opcional)
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

# Instalar dependências
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels prophet plotly
```

---

## ▶️ Como Executar
1. Abra o **Jupyter Notebook**:
   ```bash
   jupyter notebook Untitled.ipynb
   ```
2. Configure o caminho do dataset (se necessário).
3. Execute todas as células do notebook.
4. Os gráficos e previsões serão gerados automaticamente.
5. O **relatório Excel** será salvo na pasta principal.

---

## 📊 Exemplos de Análises
### **1. Evolução dos Valores**
Gráfico mostrando a série temporal com tendência linear.

### **2. Previsão de Valores Futuros**
Previsão dos próximos 6 a 12 meses com base no histórico.

### **3. Detecção de Anomalias**
Picos fora do padrão são destacados automaticamente.

### **4. Análise de Sazonalidade**
Identificação de padrões mensais e anuais.

---

## 🛠️ Próximos Passos
- Melhorar o ajuste dos modelos ARIMA e Prophet.
- Criar um **dashboard interativo** com Plotly/Dash.
- Integrar atualização automática do dataset.
- Criar versão **.exe** com interface gráfica.

---

## 👨‍💻 Autor
**Carlos Lacerda**  
📧 Email: [seu.email@example.com]  
🔗 LinkedIn: [https://linkedin.com/in/seu-perfil]

---



