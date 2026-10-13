# {py:mod}`src.models.subnets.embeddings.edges.cptp`

```{py:module} src.models.subnets.embeddings.edges.cptp
```

```{autodoc2-docstring} src.models.subnets.embeddings.edges.cptp
:allowtitles:
```

## Module Contents

### Classes

````{list-table}
:class: autosummary longtable
:align: left

* - {py:obj}`CPTPEdgeEmbedding <src.models.subnets.embeddings.edges.cptp.CPTPEdgeEmbedding>`
  - ```{autodoc2-docstring} src.models.subnets.embeddings.edges.cptp.CPTPEdgeEmbedding
    :summary:
    ```
````

### API

`````{py:class} CPTPEdgeEmbedding(embed_dim: int, linear_bias: bool = True, sparsify: bool = True, k_sparse: typing.Optional[typing.Union[int, collections.abc.Callable[[int], int]]] = None)
:canonical: src.models.subnets.embeddings.edges.cptp.CPTPEdgeEmbedding

Bases: {py:obj}`src.models.subnets.embeddings.edges.base.EdgeEmbedding`

```{autodoc2-docstring} src.models.subnets.embeddings.edges.cptp.CPTPEdgeEmbedding
```

```{rubric} Initialization
```

```{autodoc2-docstring} src.models.subnets.embeddings.edges.cptp.CPTPEdgeEmbedding.__init__
```

````{py:method} _cost_matrix_to_graph(batch_cost_matrix: torch.Tensor, init_embeddings: torch.Tensor) -> torch_geometric.data.Batch
:canonical: src.models.subnets.embeddings.edges.cptp.CPTPEdgeEmbedding._cost_matrix_to_graph

```{autodoc2-docstring} src.models.subnets.embeddings.edges.cptp.CPTPEdgeEmbedding._cost_matrix_to_graph
```

````

`````
