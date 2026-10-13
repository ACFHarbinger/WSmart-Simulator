# {py:mod}`src.envs.routing.cptp`

```{py:module} src.envs.routing.cptp
```

```{autodoc2-docstring} src.envs.routing.cptp
:allowtitles:
```

## Module Contents

### Classes

````{list-table}
:class: autosummary longtable
:align: left

* - {py:obj}`CPTPEnv <src.envs.routing.cptp.CPTPEnv>`
  - ```{autodoc2-docstring} src.envs.routing.cptp.CPTPEnv
    :summary:
    ```
````

### API

`````{py:class} CPTPEnv(generator: typing.Optional[logic.src.envs.generators.PTPGenerator] = None, generator_params: typing.Optional[dict] = None, waste_weight: float = 1.0, cost_weight: float = 1.0, revenue_kg: typing.Optional[float] = None, cost_km: typing.Optional[float] = None, device: typing.Union[str, torch.device] = 'cpu', **kwargs)
:canonical: src.envs.routing.cptp.CPTPEnv

Bases: {py:obj}`logic.src.envs.routing.ptp.PTPEnv`

```{autodoc2-docstring} src.envs.routing.cptp.CPTPEnv
```

```{rubric} Initialization
```

```{autodoc2-docstring} src.envs.routing.cptp.CPTPEnv.__init__
```

````{py:attribute} name
:canonical: src.envs.routing.cptp.CPTPEnv.name
:type: str
:value: >
   'cptp'

```{autodoc2-docstring} src.envs.routing.cptp.CPTPEnv.name
```

````

````{py:method} _reset_instance(tensordict: tensordict.TensorDict) -> tensordict.TensorDict
:canonical: src.envs.routing.cptp.CPTPEnv._reset_instance

```{autodoc2-docstring} src.envs.routing.cptp.CPTPEnv._reset_instance
```

````

````{py:method} _reset(tensordict: typing.Optional[tensordict.TensorDict] = None, **kwargs) -> tensordict.TensorDict
:canonical: src.envs.routing.cptp.CPTPEnv._reset

```{autodoc2-docstring} src.envs.routing.cptp.CPTPEnv._reset
```

````

````{py:method} _step_instance(tensordict: tensordict.TensorDict) -> tensordict.TensorDict
:canonical: src.envs.routing.cptp.CPTPEnv._step_instance

```{autodoc2-docstring} src.envs.routing.cptp.CPTPEnv._step_instance
```

````

````{py:method} _step(tensordict: tensordict.TensorDict) -> tensordict.TensorDict
:canonical: src.envs.routing.cptp.CPTPEnv._step

```{autodoc2-docstring} src.envs.routing.cptp.CPTPEnv._step
```

````

````{py:method} _get_action_mask(tensordict: tensordict.TensorDict) -> torch.Tensor
:canonical: src.envs.routing.cptp.CPTPEnv._get_action_mask

```{autodoc2-docstring} src.envs.routing.cptp.CPTPEnv._get_action_mask
```

````

`````
