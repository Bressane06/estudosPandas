# 📊 Estudos com Pandas - Análise de Dados Esportivos

Projeto de análise estatística de dados esportivos utilizando Python e Pandas
## 🗂️ Estrutura do Projeto

```
estudosPandas/
├── data/
│   ├── raw/                     # Dados originais
│   │   ├── DataBaseF1/          # 14 arquivos CSV da F1
│   │   └── libertadores-results-ds.csv
│   └── trusted/                 # Dados processados
└── notebooks/
    ├── formula1-1950-2024/
    │   ├── dadosBrasileirosF1.ipynb
    │   └── dadosGeraisF1.ipynb
    └── libertadores2011-2024/
        ├── analise-geral/
        │   └── dadosGeraisLibertadores.ipynb
        └── times-especificos/
            └── dadosCorinthians.ipynb
```

## 📈 Notebooks Disponíveis

### 🏎️ Fórmula 1
- **dadosBrasileirosF1.ipynb**: Análise dos pilotos brasileiros na F1
- **dadosGeraisF1.ipynb**: Análise geral da Fórmula 1

### 🏆 Copa Libertadores
- **dadosGeraisLibertadores.ipynb**: Estatísticas gerais da competição
- **dadosCorinthians.ipynb**: Análise específica do Corinthians

## 📊 Datasets

### Fórmula 1 (1950-2024) - 14 arquivos
| Arquivo | Descrição |
|---------|----------|
| circuits.csv | Circuitos |
| drivers.csv | Pilotos |
| constructors.csv | Construtores/Equipes |
| races.csv | Corridas |
| results.csv | Resultados das corridas |
| qualifying.csv | Classificação |
| lap_times.csv | Tempos de volta |
| pit_stops.csv | Paradas nos boxes |
| sprint_results.csv | Resultados das corridas sprint |
| driver_standings.csv | Classificação dos pilotos |
| constructor_standings.csv | Classificação dos construtores |
| constructor_results.csv | Resultados dos construtores |
| seasons.csv | Temporadas |
| status.csv | Status das corridas |

### Copa Libertadores (2011-2024)
- **libertadores-results-ds.csv**: Resultados completos da competição

## 🔗 Fontes dos Dados

- **Copa Libertadores**: [CONMEBOL Libertadores Results (Kaggle)](https://www.kaggle.com/datasets/ernestonlm/conmebol-libertadores-results-from-2011-to-2022)
- **Fórmula 1**: [Formula 1 World Championship (Kaggle)](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020/data)

## 🚀 Como Usar

1. **Dados**: Localizados em `data/raw/`
2. **Notebooks**: Organizados por competição em `notebooks/`
3. **Análises gerais**: Pasta `analise-geral/`
4. **Análises específicas**: Pasta `times-especificos/`
5. **Dados processados**: Salvar em `data/trusted/`