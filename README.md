  # 📈 Análise Comparativa de Ações Brasileiras

## 📌 Sobre o Projeto

Este projeto realiza uma análise financeira de importantes ações brasileiras utilizando Python e dados do Yahoo Finance.

O objetivo é demonstrar como coletar, processar, analisar e visualizar dados históricos do mercado financeiro de forma prática.

As análises foram desenvolvidas em um notebook Jupyter (`AdminAnáliseAções.ipynb`) e contemplam o período de:

> **Janeiro de 2023 até Maio de 2026**

---

# 🏢 Empresas Analisadas

| Empresa         | Ticker   |
| --------------- | -------- |
| Petrobras       | PETR4.SA |
| Ambev           | ABEV3.SA |
| Itaú Unibanco   | ITUB4.SA |
| Vale S.A.       | VALE3.SA |
| Banco do Brasil | BBAS3.SA |

---

# 🎯 Objetivos da Análise

Para cada empresa, o projeto busca:

* Baixar dados históricos da bolsa
* Organizar os dados em DataFrames
* Calcular métricas financeiras
* Visualizar tendências de preço
* Comparar desempenho entre empresas
* Identificar possíveis padrões de mercado

---

# 🛠️ Tecnologias Utilizadas

As seguintes bibliotecas Python foram utilizadas:

```python
pip install yfinance pandas matplotlib seaborn
```

## Bibliotecas

* `yfinance` → Download de dados financeiros
* `pandas` → Manipulação de dados
* `matplotlib` → Criação de gráficos
* `seaborn` → Estilização visual

---

# 📂 Estrutura do Projeto

```bash
.
├── AdminAnáliseAções.ipynb
└── README.md
```

---

# ▶️ Como Executar

## 1. Clone o repositório

```bash
git clone <URL_DO_REPOSITORIO>
```

## 2. Instale as dependências

```bash
pip install yfinance pandas matplotlib seaborn
```

## 3. Execute o notebook

Abra o arquivo `.ipynb` no:

* Jupyter Notebook
* Google Colab
* VS Code

---

# 📊 Exemplo de Código

```python
import yfinance as yf

# Definindo ticker
ticker = "PETR4.SA"

# Baixando dados
acao = yf.download(ticker, start="2023-01-01", end="2026-05-14")

print(acao.head())
```

---

# 📈 Visualizações

O projeto utiliza gráficos para:

* Evolução do preço das ações
* Volume de negociação
* Médias móveis
* Comparações entre ativos

---

# 📚 Conceitos Aplicados

Durante a análise são aplicados conceitos de:

* Mercado financeiro
* Análise de ações
* Ciência de dados
* Visualização de dados
* Estatística básica
* Python para finanças

---

# ⚠️ Observações

Os dados são obtidos diretamente do Yahoo Finance e podem sofrer alterações ao longo do tempo.

Este projeto possui finalidade educacional e acadêmica.

---

# 👨‍💻 Autor

Projeto desenvolvido por Ângelo Raphael.

---

# ⭐ Possíveis Melhorias Futuras

* Dashboard interativo
* Comparação automática entre ativos
* Indicadores técnicos
* Machine Learning para previsão
* Exportação automática de relatórios
* Integração com APIs financeiras

