# Optimization programming — archived coursework

> Archived 2018 Seattle University BUAN 5260 coursework. This repository
> contains R Markdown analyses of network-flow and linear optimization,
> binary integer programming with price-sensitivity simulation, and M/M/c
> queueing and inventory scenarios. It is not client or production work.

[View Afsar Ali's portfolio index](https://github.com/alidoesAi).

## Scope and authorship

- The three R Markdown analyses and the final network report identify
  **Afsar Ali** as author.
- `Network Problem.pdf` and `Optimization Problem.pdf` are course problem
  statements attributed to Gareth Green / Seattle University.
- The CSV inputs were supplied for the course.
- The network assignment allowed either individual or two-person work. The
  repository does not document whether this submission was completed alone
  or with a partner.
- Rights to redistribute the course materials and data are not documented.
  No license is granted by this repository.

## What the project demonstrates

- network maps, shortest-path reasoning, and constrained network-flow models;
- binary integer programming with explicit business rules;
- a seeded price-sensitivity simulation;
- M/M/c queueing analysis for work-in-process inventory decisions;
- decision-oriented tables, visualizations, and written recommendations.

## Artifacts

### Network optimization

- [Problem statement](./Network%20Problem.pdf)
- [Course-provided data](./5260_S18_Aiding_Africa_Data.csv)
- [R Markdown source](./Network%20optimization%20model%20EDA.Rmd)
- [Rendered analysis](https://alidoesai.github.io/Optimization-programming/Network_optimization_model_EDA.html)
- [Final report](https://alidoesai.github.io/Optimization-programming/Network%20optimization%20model.pdf)

### Integer programming and queueing/inventory analysis

- [Problem statement](./Optimization%20Problem.pdf)
- [Course-provided data](./5260_S18_Arties_Dream.csv)
- [Integer-programming R Markdown source](./Integer%20programming%20model.Rmd)
- [Rendered integer-programming analysis](https://alidoesai.github.io/Optimization-programming/Integer_programming_model.html)
- [Queueing/inventory R Markdown source](./Inventory%20optimization%20model.Rmd)
- [Rendered queueing/inventory analysis](https://alidoesai.github.io/Optimization-programming/Inventory_optimization_model.html)

## Runtime and reproducibility status

The source uses R packages including `igraph`, `lpSolve`, `lpSolveAPI`,
`tidyverse`, `magrittr`, `data.table`, `reshape2`, `queueing`, `knitr`,
`kableExtra`, and `formattable`. R and package versions were not recorded,
and the repository has no lockfile, automated test, continuous-integration
workflow, or verified one-command render. The archived outputs have not been
rerun under a current environment.
