# Floyd-Warshall x n-Dijkstra: avaliação teórica e empírica

> Notebook que compara o algoritmo de Floyd-Warshall com `n` execuções de Dijkstra para caminhos mínimos entre todos os pares, em complexidade e em tempo medido.

![status](https://img.shields.io/badge/status-concluído-success) ![python](https://img.shields.io/badge/Python-3-blue) ![jupyter](https://img.shields.io/badge/Jupyter-notebook-orange)

## Sobre
Trabalho da disciplina de Projeto e Análise de Algoritmos da pós-graduação (2020). Os dois algoritmos são implementados sobre matriz de adjacência; grafos aleatórios de 1 a 1000 vértices são gerados e o tempo de execução é registrado em CSV e plotado (arquivos `time_execution_*.html`). A análise teórica discute `O(n³)` do Floyd-Warshall contra `O(n · (V² ))` do n-Dijkstra sem heap e onde cada um vence na prática.

## Estrutura de pastas
```text
Submissão_2_[Floyd_x_Dijkstra]_(Avaliação_Teórica).ipynb   implementação, coleta de tempos e gráficos
time_execution_[1 - 5].html                                 gráfico para grafos pequenos
_time_execution_[1 - 100]_*.html                            gráfico para 1 a 100 vértices
outros_dados/                                               execuções adicionais (até 1000 vértices)
versoes-anteriores/                                         primeira versão da submissão
```

## Como executar
```bash
pip install jupyter numpy pandas plotly
jupyter notebook
```

## Status
Concluído. As resoluções das listas da mesma disciplina estão em [resolucao-listas-paa](https://github.com/RonildoSilva/resolucao-listas-paa).

## Autor
Ronildo Silva · ronildo.comp@gmail.com
