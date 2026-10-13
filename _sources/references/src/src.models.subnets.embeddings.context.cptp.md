# {py:mod}`src.models.subnets.embeddings.context.cptp`

```{py:module} src.models.subnets.embeddings.context.cptp
```

```{autodoc2-docstring} src.models.subnets.embeddings.context.cptp
:allowtitles:
```

## Module Contents

### Classes

````{list-table}
:class: autosummary longtable
:align: left

* - {py:obj}`CPTPContextEmbedder <src.models.subnets.embeddings.context.cptp.CPTPContextEmbedder>`
  - ```{autodoc2-docstring} src.models.subnets.embeddings.context.cptp.CPTPContextEmbedder
    :summary:
    ```
````

### API

`````{py:class} CPTPContextEmbedder(embed_dim: int, node_dim: int = NODE_DIM, temporal_horizon: int = 0)
:canonical: src.models.subnets.embeddings.context.cptp.CPTPContextEmbedder

Bases: {py:obj}`src.models.subnets.embeddings.context.base.ContextEmbedder`

```{autodoc2-docstring} src.models.subnets.embeddings.context.cptp.CPTPContextEmbedder
```

```{rubric} Initialization
```

```{autodoc2-docstring} src.models.subnets.embeddings.context.cptp.CPTPContextEmbedder.__init__
```

````{py:method} init_node_embeddings(nodes: typing.Dict[str, typing.Any], temporal_features: bool = True) -> torch.Tensor
:canonical: src.models.subnets.embeddings.context.cptp.CPTPContextEmbedder.init_node_embeddings

```{autodoc2-docstring} src.models.subnets.embeddings.context.cptp.CPTPContextEmbedder.init_node_embeddings
```

````

````{py:method} _step_context(embeddings: torch.Tensor, state: typing.Any) -> torch.Tensor
:canonical: src.models.subnets.embeddings.context.cptp.CPTPContextEmbedder._step_context

```{autodoc2-docstring} src.models.subnets.embeddings.context.cptp.CPTPContextEmbedder._step_context
```

````

````{py:property} step_context_dim
:canonical: src.models.subnets.embeddings.context.cptp.CPTPContextEmbedder.step_context_dim
:type: int

```{autodoc2-docstring} src.models.subnets.embeddings.context.cptp.CPTPContextEmbedder.step_context_dim
```

````

`````
