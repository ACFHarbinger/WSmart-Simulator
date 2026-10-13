# {py:mod}`src.models.subnets.embeddings.cptp`

```{py:module} src.models.subnets.embeddings.cptp
```

```{autodoc2-docstring} src.models.subnets.embeddings.cptp
:allowtitles:
```

## Module Contents

### Classes

````{list-table}
:class: autosummary longtable
:align: left

* - {py:obj}`CPTPInitEmbedding <src.models.subnets.embeddings.cptp.CPTPInitEmbedding>`
  - ```{autodoc2-docstring} src.models.subnets.embeddings.cptp.CPTPInitEmbedding
    :summary:
    ```
````

### API

`````{py:class} CPTPInitEmbedding(embed_dim: int = 128, node_dim: int = 3, temporal_horizon: int = 0, legacy_depot_projection: bool = False)
:canonical: src.models.subnets.embeddings.cptp.CPTPInitEmbedding

Bases: {py:obj}`torch.nn.Module`

```{autodoc2-docstring} src.models.subnets.embeddings.cptp.CPTPInitEmbedding
```

```{rubric} Initialization
```

```{autodoc2-docstring} src.models.subnets.embeddings.cptp.CPTPInitEmbedding.__init__
```

````{py:method} forward(td: typing.Union[tensordict.TensorDict, typing.Dict[str, typing.Any]], temporal_features: bool = True) -> torch.Tensor
:canonical: src.models.subnets.embeddings.cptp.CPTPInitEmbedding.forward

```{autodoc2-docstring} src.models.subnets.embeddings.cptp.CPTPInitEmbedding.forward
```

````

````{py:method} init_node_embeddings(nodes: typing.Any, *args: typing.Any, **kwargs: typing.Any) -> torch.Tensor
:canonical: src.models.subnets.embeddings.cptp.CPTPInitEmbedding.init_node_embeddings

```{autodoc2-docstring} src.models.subnets.embeddings.cptp.CPTPInitEmbedding.init_node_embeddings
```

````

`````
