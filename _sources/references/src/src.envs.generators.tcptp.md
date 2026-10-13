# {py:mod}`src.envs.generators.tcptp`

```{py:module} src.envs.generators.tcptp
```

```{autodoc2-docstring} src.envs.generators.tcptp
:allowtitles:
```

## Module Contents

### Classes

````{list-table}
:class: autosummary longtable
:align: left

* - {py:obj}`TCPTPGenerator <src.envs.generators.tcptp.TCPTPGenerator>`
  - ```{autodoc2-docstring} src.envs.generators.tcptp.TCPTPGenerator
    :summary:
    ```
````

### API

`````{py:class} TCPTPGenerator(*args, shift_hours: typing.Union[float, None] = None, avg_speed_kmh: typing.Union[float, None] = None, service_time_h: typing.Union[float, None] = None, **kwargs)
:canonical: src.envs.generators.tcptp.TCPTPGenerator

Bases: {py:obj}`logic.src.envs.generators.ptp.PTPGenerator`

```{autodoc2-docstring} src.envs.generators.tcptp.TCPTPGenerator
```

```{rubric} Initialization
```

```{autodoc2-docstring} src.envs.generators.tcptp.TCPTPGenerator.__init__
```

````{py:method} _generate(batch_size: tuple[int, ...]) -> tensordict.TensorDict
:canonical: src.envs.generators.tcptp.TCPTPGenerator._generate

```{autodoc2-docstring} src.envs.generators.tcptp.TCPTPGenerator._generate
```

````

`````
