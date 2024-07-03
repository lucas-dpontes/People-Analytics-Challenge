# People-Analytics-Challenge

Data analysis project developed as part of the People Analytics challenge, promoted by the **[Data Vinking](https://www.dataviking.com.br/)** data community.

Team Members:
- Lucas Pontes *[profile](https://www.linkedin.com/in/lucasdpontes/)*
- Pedro Borges: https*[profile](https://www.linkedin.com/in/pedrogborges/)*

<br><br><h1 align="center">Introdução</h1>

This study conducted analyzes of a Human Resources database to understand the high employee turnover in a company.

Throughout the analysis, different aspects related to the permanence of employees at a Software House company were explored.

Business Pain
- High hiring and resign costs
- Low retention impacts ongoing projects and learning curves
- Training expenses

<br><br><h1 align="center">Analysis</h1>

## Average length of stay

Firstly, the average length of stay of employees was examined, offering an overview of the stability of the workforce over time.

```mermaid
---
title: Average length of stay
---
flowchart LR
    id1([17.5 months])
```

## Turnover Cycles

Then, turnover cycles were identified, according the chart below, to highlight specific periods in which there were spikes in employee departures from the company.

<br><p align="center"><img src="https://github.com/lucas-dpontes/People-Analytics-Challenge/blob/main/historico_contratacao.PNG?raw=true"></p>

Based on the hiring history, this value was increased in the 4th quarter of 2023.

In the second quarter of 2024, specifically on March 15, there were 144 layoffs, indicating a **possible mass layoff** scenario.

## Risk profile

In addition, the risk profile of employees was investigated, comparing those who left the company with those who stayed to understand whether higher satisfaction or performance were directly related to these departures.

## Correlations

Statistical analyzes were also carried out to identify correlations between the variables in the database, seeking to better understand the factors underlying high turnover.

```mermaid
flowchart LR
    id1(Encontrada alta correlação entre a idade e salário dos funcionários)
```

<p align="center"><img src="https://github.com/lucas-dpontes/People-Analytics-Challenge/blob/main/heatmap.PNG?raw=true"></p>

## mployees with 2+ years at the company

Finally, employees with up to 2 years at the company were compared with those with 2+ years, seeking to identify possible discrepancies that could provide additional insights about retention.

<br><br><h1 align="center">Conclusions</h1>

Após analisar o perfil dos funcionários desligados e não desligados, observamos que todos os funcionários foram desligados no mesmo dia, sugerindo uma ação coletiva ou uma decisão organizacional em massa. Além disso, constatamos que a satisfação média dos funcionários desligados era significativamente menor do que a dos funcionários não desligados, indicando uma possível relação entre insatisfação e saída da empresa.

Surpreendentemente, descobrimos que o desempenho dos funcionários desligados era, em média, maior do que o dos funcionários não desligados. Isso pode sugerir que outros fatores, além do desempenho no trabalho, estão contribuindo para a rotatividade de pessoal, como questões de cultura organizacional, falta de oportunidades de crescimento ou desalinhamento de expectativas.

Essas descobertas ressaltam a importância de uma abordagem multidisciplinar para a retenção de talentos, que leve em consideração não apenas o desempenho individual, mas também o engajamento, a satisfação e o bem-estar dos funcionários. Ao abordar esses aspectos, as organizações podem criar um ambiente de trabalho mais positivo e motivador, reduzindo assim a rotatividade de funcionários e promovendo a retenção de talentos de forma eficaz.
