# Deezer Ego-Net Gender Classification

Este repositório contém o projeto desenvolvido para a disciplina **Aprendizado de Máquina I** (UFSCar - 2025/1), ministrada pelo Prof. Dr. Murilo Naldi.

O objetivo do trabalho é aplicar técnicas de aprendizado supervisionado para **prever o gênero** de um usuário (nó ego) com base na estrutura de sua ego-net na rede social musical **Deezer**.

## 👤 Dataset

Utilizamos o dataset **Deezer Ego Nets**, que contém 9.629 grafos não direcionados, cada um representando a rede de seguidores de um usuário do leste europeu. O nó central (ego) de cada grafo possui um rótulo binário indicando o gênero (masculino ou feminino).

- Fonte: [SNAP - Stanford Network Analysis Project](https://snap.stanford.edu/data/deezer_ego_nets.html)
- Tarefa: Classificação binária
- Atributos dos nós: Nenhum
- Atributos das arestas: Nenhum

## 🎯 Objetivos do projeto

1. **Exploração e preparação dos dados**
   - Leitura e representação dos grafos
   - Extração de atributos estruturais relevantes (grau, densidade, clustering, etc.)
   - Preparação do dataset final com features úteis

2. **Modelagem**
   - Aplicação de modelos supervisionados para classificação
   - Avaliação de desempenho com métricas adequadas
   - Comparação entre diferentes algoritmos

3. **Apresentação**
   - Relatório científico conforme especificações da disciplina
   - Vídeo de apresentação com explicação dos resultados

## 🛠️ Tecnologias

- Linguagem: **Python 3**
- Bibliotecas (a definir, mas possivelmente):
  - NetworkX (manipulação de grafos)
  - scikit-learn (modelos e avaliação)
  - Pandas, NumPy (pré-processamento)
  - Matplotlib, Seaborn (visualização)

> As bibliotecas e frameworks utilizados serão definidos ao longo do desenvolvimento.

## 👥 Integrantes

- Gustavo Kim Alcantara — RA 820763
- Gabriel Mello Silveira Targas — RA 812990
