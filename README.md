# Image-Graph

Representação e análise estrutural de imagens em escala de cinza por meio de grafos, desenvolvida para a disciplina **ECO0046 — Algoritmos em Grafos** (Semestre 2026.2), pela Equipe 5 (Nicole Souza Batista, Pablo Hugo Freitas Alves e Karen Stephan da Penha Sousa)

## Como inicializar o repositório?

O projeto utiliza o [`uv`](https://docs.astral.sh/uv/) para gerenciamento de ambiente virtual e dependências (`pyproject.toml` e `uv.lock`).

### 1. Clonar o repositório
```bash
git clone https://github.com/pab-h/image-graph.git
cd Image-Graph
```

### 2. Criar o ambiente e instalar as dependências

```bash
uv sync
```

### 3. Executar o projeto

```bash
uv run python src/main.py
```


## Estrutura do repositório


* **`src/algorithms.py`**: Implementação dos algoritmos em grafos (construção do grafo a partir da matriz de pixels, busca em largura/profundidade para componentes conexas, e DFS com `low[]` para identificação de pontes e vértices de articulação).


* **`src/main.py`**: Ponto de entrada para execução dos experimentos, extração de métricas estruturais e geração de saídas/visualizações.

* **`notebooks/`**: Notebooks Jupyter para documentar experimentos, visualizações das regiões/componentes e comparações de modelos.
