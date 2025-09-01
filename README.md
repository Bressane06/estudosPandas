# Estudos com Pandas - Análise de Dados Esportivos

Este projeto contém análises estatísticas de dados esportivos utilizando Python e Pandas, focando em Copa Libertadores (2011-2024) e Fórmula 1 (1950-2020).

## Fonte dos Dados

- **Copa Libertadores (2011-2022)**: [CONMEBOL Libertadores Results from 2011 to 2022](https://www.kaggle.com/datasets/ernestonlm/conmebol-libertadores-results-from-2011-to-2022)
- **Fórmula 1 (1950-2020)**: [Formula 1 World Championship (1950-2020)](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020/data)

## Estrutura do Projeto

```
estudosPandas/
├── data/
│   ├── raw/
│   │   ├── DataBaseF1/          # Dados da Fórmula 1 (14 arquivos CSV)
│   │   └── libertadores-results-ds.csv
│   └── trusted/                 # Dados processados
└── notebooks/
    ├── formula1-1950-2024/
    │   └── dadosBrasileirosF1.ipynb
    └── libertadores2011-2024/
        ├── analise-geral/
        │   └── dadosGeraisLibertadores.ipynb
        └── times-especificos/
            └── dadosCorinthians.ipynb
```

## Datasets Disponíveis

### Fórmula 1 (1950-2020)
- circuits.csv - Circuitos
- drivers.csv - Pilotos
- constructors.csv - Construtores/Equipes
- races.csv - Corridas
- results.csv - Resultados das corridas
- qualifying.csv - Classificação
- lap_times.csv - Tempos de volta
- pit_stops.csv - Paradas nos boxes
- sprint_results.csv - Resultados das corridas sprint
- driver_standings.csv - Classificação dos pilotos
- constructor_standings.csv - Classificação dos construtores
- constructor_results.csv - Resultados dos construtores
- seasons.csv - Temporadas
- status.csv - Status das corridas

### Copa Libertadores (2011-2022)
- libertadores-results-ds.csv - Resultados completos da competição

## Notebooks Disponíveis

### Fórmula 1
- `notebooks/formula1-1950-2024/dadosBrasileirosF1.ipynb`: Análise dos pilotos brasileiros na F1

### Copa Libertadores
- `notebooks/libertadores2011-2024/analise-geral/dadosGeraisLibertadores.ipynb`: Análise geral da competição
- `notebooks/libertadores2011-2024/times-especificos/dadosCorinthians.ipynb`: Análise específica do Corinthians

## Como usar

1. Os dados estão organizados na pasta `data/raw/`
2. Notebooks estão organizados por competição em `notebooks/`
3. Para análises gerais: use as pastas `analise-geral/`
4. Para análises específicas: use as pastas `times-especificos/` ou crie notebooks específicos
5. Dados processados podem ser salvos em `data/trusted/`