# {py:mod}`src.policies.mandatory_selection.selection_filter_and_fan`

```{py:module} src.policies.mandatory_selection.selection_filter_and_fan
```

```{autodoc2-docstring} src.policies.mandatory_selection.selection_filter_and_fan
:allowtitles:
```

## Module Contents

### Classes

````{list-table}
:class: autosummary longtable
:align: left

* - {py:obj}`FilterAndFanSelection <src.policies.mandatory_selection.selection_filter_and_fan.FilterAndFanSelection>`
  - ```{autodoc2-docstring} src.policies.mandatory_selection.selection_filter_and_fan.FilterAndFanSelection
    :summary:
    ```
````

### API

`````{py:class} FilterAndFanSelection(filter_width: typing.Optional[int] = None, fan_depth: typing.Optional[int] = None)
:canonical: src.policies.mandatory_selection.selection_filter_and_fan.FilterAndFanSelection

Bases: {py:obj}`logic.src.interfaces.mandatory_selection.IMandatorySelectionStrategy`

```{autodoc2-docstring} src.policies.mandatory_selection.selection_filter_and_fan.FilterAndFanSelection
```

```{rubric} Initialization
```

```{autodoc2-docstring} src.policies.mandatory_selection.selection_filter_and_fan.FilterAndFanSelection.__init__
```

````{py:method} select_bins(context: logic.src.interfaces.context.SelectionContext) -> typing.Tuple[typing.List[int], logic.src.interfaces.context.SearchContext]
:canonical: src.policies.mandatory_selection.selection_filter_and_fan.FilterAndFanSelection.select_bins

```{autodoc2-docstring} src.policies.mandatory_selection.selection_filter_and_fan.FilterAndFanSelection.select_bins
```

````

`````
