# {py:mod}`src.envs.routing.tcptp`

```{py:module} src.envs.routing.tcptp
```

```{autodoc2-docstring} src.envs.routing.tcptp
:allowtitles:
```

## Module Contents

### Classes

````{list-table}
:class: autosummary longtable
:align: left

* - {py:obj}`TCPTPEnv <src.envs.routing.tcptp.TCPTPEnv>`
  - ```{autodoc2-docstring} src.envs.routing.tcptp.TCPTPEnv
    :summary:
    ```
````

### API

`````{py:class} TCPTPEnv(generator: typing.Optional[logic.src.envs.generators.tcptp.TCPTPGenerator] = None, generator_params: typing.Optional[dict] = None, waste_weight: float = 1.0, cost_weight: float = 1.0, revenue_kg: typing.Optional[float] = None, cost_km: typing.Optional[float] = None, device: typing.Union[str, torch.device] = 'cpu', **kwargs)
:canonical: src.envs.routing.tcptp.TCPTPEnv

Bases: {py:obj}`logic.src.envs.routing.cptp.CPTPEnv`

```{autodoc2-docstring} src.envs.routing.tcptp.TCPTPEnv
```

```{rubric} Initialization
```

```{autodoc2-docstring} src.envs.routing.tcptp.TCPTPEnv.__init__
```

````{py:attribute} name
:canonical: src.envs.routing.tcptp.TCPTPEnv.name
:type: str
:value: >
   'tcptp'

```{autodoc2-docstring} src.envs.routing.tcptp.TCPTPEnv.name
```

````

````{py:method} _reset_instance(tensordict: tensordict.TensorDict) -> tensordict.TensorDict
:canonical: src.envs.routing.tcptp.TCPTPEnv._reset_instance

```{autodoc2-docstring} src.envs.routing.tcptp.TCPTPEnv._reset_instance
```

````

````{py:method} _reset(tensordict: typing.Optional[tensordict.TensorDict] = None, **kwargs) -> tensordict.TensorDict
:canonical: src.envs.routing.tcptp.TCPTPEnv._reset

```{autodoc2-docstring} src.envs.routing.tcptp.TCPTPEnv._reset
```

````

````{py:method} _step(tensordict: tensordict.TensorDict) -> tensordict.TensorDict
:canonical: src.envs.routing.tcptp.TCPTPEnv._step

```{autodoc2-docstring} src.envs.routing.tcptp.TCPTPEnv._step
```

````

````{py:method} _step_instance(tensordict: tensordict.TensorDict) -> tensordict.TensorDict
:canonical: src.envs.routing.tcptp.TCPTPEnv._step_instance

```{autodoc2-docstring} src.envs.routing.tcptp.TCPTPEnv._step_instance
```

````

````{py:method} _get_action_mask(tensordict: tensordict.TensorDict) -> torch.Tensor
:canonical: src.envs.routing.tcptp.TCPTPEnv._get_action_mask

```{autodoc2-docstring} src.envs.routing.tcptp.TCPTPEnv._get_action_mask
```

````

````{py:method} _check_done(tensordict: tensordict.TensorDict) -> torch.Tensor
:canonical: src.envs.routing.tcptp.TCPTPEnv._check_done

```{autodoc2-docstring} src.envs.routing.tcptp.TCPTPEnv._check_done
```

````

`````
