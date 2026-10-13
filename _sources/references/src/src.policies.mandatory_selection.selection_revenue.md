# {py:mod}`src.policies.mandatory_selection.selection_revenue`

```{py:module} src.policies.mandatory_selection.selection_revenue
```

```{autodoc2-docstring} src.policies.mandatory_selection.selection_revenue
:allowtitles:
```

## Module Contents

### Classes

````{list-table}
:class: autosummary longtable
:align: left

* - {py:obj}`RevenueThresholdSelection <src.policies.mandatory_selection.selection_revenue.RevenueThresholdSelection>`
  - ```{autodoc2-docstring} src.policies.mandatory_selection.selection_revenue.RevenueThresholdSelection
    :summary:
    ```
````

### API

`````{py:class} RevenueThresholdSelection(revenue_kg: typing.Optional[float] = None, revenue_threshold: typing.Optional[float] = None)
:canonical: src.policies.mandatory_selection.selection_revenue.RevenueThresholdSelection

Bases: {py:obj}`logic.src.interfaces.mandatory_selection.IMandatorySelectionStrategy`

```{autodoc2-docstring} src.policies.mandatory_selection.selection_revenue.RevenueThresholdSelection
```

```{rubric} Initialization
```

```{autodoc2-docstring} src.policies.mandatory_selection.selection_revenue.RevenueThresholdSelection.__init__
```

````{py:method} select_bins(context: logic.src.interfaces.context.SelectionContext) -> typing.Tuple[typing.List[int], logic.src.interfaces.context.SearchContext]
:canonical: src.policies.mandatory_selection.selection_revenue.RevenueThresholdSelection.select_bins

```{autodoc2-docstring} src.policies.mandatory_selection.selection_revenue.RevenueThresholdSelection.select_bins
```

````

`````
