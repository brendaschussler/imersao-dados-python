# 📊 Dashboard de Análise de Salários na Área de Dados

![Dashboard Preview](https://github.com/brendaschussler/imersao-dados-python/blob/main/dashboard_preview.png)

## 🔍 Visão Geral
Dashboard interativo que analisa salários na área de dados (Data Science, Análise de Dados, Engenharia de Dados) com filtros dinâmicos e visualizações interativas construído com Streamlit.

**Acesse o dashboard online:** [https://imersao-dados-python.streamlit.app/](https://imersao-dados-python.streamlit.app/)

## ✨ Funcionalidades
- **Filtros interativos** por:
  - Ano
  - Nível de senioridade
  - Tipo de contrato
  - Tamanho da empresa
    
- **Visualizações dinâmicas**:
  - Gráficos atualizados em tempo real
  - Mapa mundial interativo
  - Tabela de dados filtrada
    
- **KPIs principais**:
  - Salário médio e máximo
  - Total de registros
  - Cargo mais frequente

## 📊 Gráficos Disponíveis
1. **Top 10 cargos** por salário médio (horizontal bar chart)
2. **Distribuição salarial** (histograma)
3. **Proporção de modelos de trabalho** (remoto/híbrido/presencial)
4. **Mapa de calor por país** (salário médio de Data Scientists)

## 🛠️ Tecnologias
```python
streamlit==1.29.0
pandas==2.1.4
plotly==5.18.0
```

## 🚀 Como Executar Localmente
```
# Clone o repositório
git clone https://github.com/brendaschussler/imersao-dados-python.git

# Acesse a pasta do projeto
cd imersao-dados-python

# Instale as dependências
pip install -r requirements.txt

# Execute o dashboard
streamlit run app.py
```
