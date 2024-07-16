# Visualização de Algoritmos de Monte Carlo e Representação de 4D

Este repositório contém dois notebooks principais que abordam a visualização de algoritmos de Monte Carlo e a representação de hipersuperfícies em 4D utilizando diferentes abordagens.

## Conteúdo

1. [monte_carlos_4D.ipynb](monte_carlos_4D.ipynb)
2. [representacao_4D.ipynb](representacao_4D.ipynb)

## Requisitos

- Python 3.x
- Bibliotecas:
  - numpy
  - plotly

Você pode instalar as bibliotecas necessárias usando pip:

```bash
pip install numpy plotly
```

## monte_carlos_4D.ipynb

### Descrição

Este notebook implementa um algoritmo de Monte Carlo para encontrar o melhor caminho em uma função matemática definida em 4D. O notebook explora diferentes abordagens para interpretar as quatro dimensões e visualiza os resultados utilizando gráficos interativos com Plotly.

### Abordagens

- 4 Dimensões Espaciais (x, y, z, w)
- 2 Dimensões Espaciais e 2 Temporais (x, y, t1, t2)
- 3 Dimensões Temporais e 1 Espacial (t1, t2, t3, x)
- 3 Dimensões Temporais e 2 Espaciais (t1, t2, t3, x, y)
- 3 Dimensões Temporais e 3 Espaciais (t1, t2, t3, x, y, z)

### Execução

Para executar o notebook, siga os passos abaixo:

1. Abra o Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Navegue até `monte_carlos_4D.ipynb` e abra-o.
3. Execute as células sequencialmente para gerar as visualizações dos caminhos de Monte Carlo e das hipersuperfícies em 4D.

## representacao_4D.ipynb

### Descrição

Este notebook aborda a representação de hipersuperfícies em 4D utilizando diferentes técnicas de projeção para visualizá-las em 3D. O foco é criar visualizações compreensíveis de hipersuperfícies complexas projetadas para 3D e demonstrar várias formas de representar a quarta dimensão.

### Execução

Para executar o notebook, siga os passos abaixo:

1. Abra o Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Navegue até `representacao_4D.ipynb` e abra-o.
3. Execute as células sequencialmente para gerar as visualizações das hipersuperfícies em 4D.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.
Esse conteúdo fornece uma visão geral e instruções sobre como usar os notebooks, garantindo que os usuários possam facilmente entender e executar os códigos.
