# Análise de Notas de Filmes

Este projeto realiza uma análise básica das notas de filmes utilizando um conjunto de dados de classificações de filmes. O código foi desenvolvido e executado no Google Colab, e pode ser facilmente reproduzido clicando no botão "Open in Colab" abaixo.

## Open In Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/usuario/repositorio/nome_do_notebook.ipynb)

## Descrição do Projeto

O projeto faz a leitura de um arquivo CSV contendo as notas de filmes e realiza algumas operações básicas de análise de dados, como:

- Leitura e visualização das primeiras linhas do dataset
- Renomeação das colunas
- Verificação das notas únicas
- Contagem das ocorrências de cada nota
- Cálculo da média das notas

## Dados Utilizados

O dataset utilizado no projeto contém as seguintes colunas:

- `usuarioID`: ID do usuário que avaliou o filme
- `filmeID`: ID do filme avaliado
- `nota`: Nota atribuída ao filme (de 0.5 a 5.0)
- `momento`: Timestamp da avaliação

### Visualização Inicial dos Dados

```python
import pandas as pd
notas = pd.read_csv("ratings.csv")
notas.head()
