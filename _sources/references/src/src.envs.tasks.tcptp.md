# {py:mod}`src.envs.tasks.tcptp`

```{py:module} src.envs.tasks.tcptp
```

```{autodoc2-docstring} src.envs.tasks.tcptp
:allowtitles:
```

## Module Contents

### Classes

````{list-table}
:class: autosummary longtable
:align: left

* - {py:obj}`TCPTP <src.envs.tasks.tcptp.TCPTP>`
  - ```{autodoc2-docstring} src.envs.tasks.tcptp.TCPTP
    :summary:
    ```
````

### API

`````{py:class} TCPTP
:canonical: src.envs.tasks.tcptp.TCPTP

Bases: {py:obj}`logic.src.envs.tasks.cptp.CPTP`

```{autodoc2-docstring} src.envs.tasks.tcptp.TCPTP
```

````{py:attribute} NAME
:canonical: src.envs.tasks.tcptp.TCPTP.NAME
:value: >
   'tcptp'

```{autodoc2-docstring} src.envs.tasks.tcptp.TCPTP.NAME
```

````

````{py:method} get_costs(dataset: typing.Dict[str, typing.Any], pi: torch.Tensor, cw_dict: typing.Optional[typing.Dict[str, float]], dist_matrix: typing.Optional[torch.Tensor] = None) -> typing.Tuple[torch.Tensor, typing.Dict[str, torch.Tensor], None]
:canonical: src.envs.tasks.tcptp.TCPTP.get_costs
:staticmethod:

```{autodoc2-docstring} src.envs.tasks.tcptp.TCPTP.get_costs
```

````

`````
