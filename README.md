# Análise Global do Câncer – GBD 2023

Análise exploratória e visualização de dados sobre o perfil global do câncer com base nos dados do **Global Burden of Disease (GBD) 2023**, publicados pelo Institute for Health Metrics and Evaluation (IHME).

---

## Pergunta de Pesquisa

> **Quais cânceres representam o maior desafio global entre 2013 e 2023 — considerando incidência, mortalidade, prevalência e impacto na população?**

---

## Estrutura do Projeto

```
├── cancer_gbd2023_retificado.ipynb   # Notebook principal com análise e visualizações
├── IHME-GBD_2023_DATA-91be50d1-1.csv # Dataset original do GBD 2023
├── Relatorio_Cancer_GBD2023.pdf      # Relatório completo da análise
├── Analise_Global_Cancer_GBD2023.pptx # Apresentação dos resultados
```

---

## Conteúdo do Notebook

### Bloco 1 — Preparação dos Dados
- Importação de bibliotecas (pandas, matplotlib, seaborn)
- Funções auxiliares de formatação e validação
- Carregamento e limpeza do dataset GBD
- Remoção de colunas constantes, categorias agregadas e registros não relacionados ao câncer

### Bloco 2 — Análise Descritiva
- **Incidência**: evolução dos casos novos ao longo do tempo
- **Mortalidade**: quais cânceres mais matam
- **Taxa de Letalidade**: razão entre mortes e casos novos por tipo de câncer
- **Prevalência**: quantas pessoas vivem com diagnóstico de câncer

### Bloco 3 — Análise Avançada
- **Perfil de agressividade**: dispersão incidência × mortalidade para classificar cânceres por volume e letalidade

---

## Fonte dos Dados

- **IHME – Global Burden of Disease 2023**
- Acesso: [healthdata.org](https://www.healthdata.org/research-analysis/gbd)
- Arquivo: `IHME-GBD_2023_DATA-91be50d1-1.csv`

---

## Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/fredmartins12/visualizacao-de-dados.git
```

2. Instale as dependências:
```bash
pip install pandas matplotlib seaborn jupyter
```

3. Coloque o arquivo `.csv` na mesma pasta do notebook e abra:
```bash
jupyter notebook cancer_gbd2023_retificado.ipynb
```

---

## Tecnologias

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red)
