# {py:mod}`src.policies.mandatory_selection.base.selection_factory`

```{py:module} src.policies.mandatory_selection.base.selection_factory
```

```{autodoc2-docstring} src.policies.mandatory_selection.base.selection_factory
:allowtitles:
```

## Module Contents

### Classes

````{list-table}
:class: autosummary longtable
:align: left

* - {py:obj}`MandatorySelectionFactory <src.policies.mandatory_selection.base.selection_factory.MandatorySelectionFactory>`
  - ```{autodoc2-docstring} src.policies.mandatory_selection.base.selection_factory.MandatorySelectionFactory
    :summary:
    ```
````

### Functions

````{list-table}
:class: autosummary longtable
:align: left

* - {py:obj}`_instantiate <src.policies.mandatory_selection.base.selection_factory._instantiate>`
  - ```{autodoc2-docstring} src.policies.mandatory_selection.base.selection_factory._instantiate
    :summary:
    ```
````

### Data

````{list-table}
:class: autosummary longtable
:align: left

* - {py:obj}`logger <src.policies.mandatory_selection.base.selection_factory.logger>`
  - ```{autodoc2-docstring} src.policies.mandatory_selection.base.selection_factory.logger
    :summary:
    ```
* - {py:obj}`CONFIG_MAPPING <src.policies.mandatory_selection.base.selection_factory.CONFIG_MAPPING>`
  - ```{autodoc2-docstring} src.policies.mandatory_selection.base.selection_factory.CONFIG_MAPPING
    :summary:
    ```
````

### API

````{py:data} logger
:canonical: src.policies.mandatory_selection.base.selection_factory.logger
:value: >
   'getLogger(...)'

```{autodoc2-docstring} src.policies.mandatory_selection.base.selection_factory.logger
```

````

````{py:function} _instantiate(strategy_cls: typing.Any, kwargs: dict, name: str) -> typing.Any
:canonical: src.policies.mandatory_selection.base.selection_factory._instantiate

```{autodoc2-docstring} src.policies.mandatory_selection.base.selection_factory._instantiate
```
````

````{py:data} CONFIG_MAPPING
:canonical: src.policies.mandatory_selection.base.selection_factory.CONFIG_MAPPING
:value: >
   None

```{autodoc2-docstring} src.policies.mandatory_selection.base.selection_factory.CONFIG_MAPPING
```

````

`````{py:class} MandatorySelectionFactory
:canonical: src.policies.mandatory_selection.base.selection_factory.MandatorySelectionFactory

```{autodoc2-docstring} src.policies.mandatory_selection.base.selection_factory.MandatorySelectionFactory
```

````{py:method} create_strategy(name: str, **kwargs) -> logic.src.interfaces.mandatory_selection.IMandatorySelectionStrategy
:canonical: src.policies.mandatory_selection.base.selection_factory.MandatorySelectionFactory.create_strategy
:staticmethod:

```{autodoc2-docstring} src.policies.mandatory_selection.base.selection_factory.MandatorySelectionFactory.create_strategy
```

````

````{py:method} create_from_config(config: typing.Any) -> logic.src.interfaces.mandatory_selection.IMandatorySelectionStrategy
:canonical: src.policies.mandatory_selection.base.selection_factory.MandatorySelectionFactory.create_from_config
:classmethod:

```{autodoc2-docstring} src.policies.mandatory_selection.base.selection_factory.MandatorySelectionFactory.create_from_config
```

````

`````
