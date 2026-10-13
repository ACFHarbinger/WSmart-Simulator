# {py:mod}`src.policies.mandatory_selection.selection_dispatcher_portfolio`

```{py:module} src.policies.mandatory_selection.selection_dispatcher_portfolio
```

```{autodoc2-docstring} src.policies.mandatory_selection.selection_dispatcher_portfolio
:allowtitles:
```

## Module Contents

### Classes

````{list-table}
:class: autosummary longtable
:align: left

* - {py:obj}`PortfolioDispatcher <src.policies.mandatory_selection.selection_dispatcher_portfolio.PortfolioDispatcher>`
  - ```{autodoc2-docstring} src.policies.mandatory_selection.selection_dispatcher_portfolio.PortfolioDispatcher
    :summary:
    ```
````

### API

`````{py:class} PortfolioDispatcher(dispatcher_mode: typing.Optional[str] = None, dispatcher_candidate_strategies: typing.Optional[typing.List[str]] = None)
:canonical: src.policies.mandatory_selection.selection_dispatcher_portfolio.PortfolioDispatcher

Bases: {py:obj}`logic.src.interfaces.mandatory_selection.IMandatorySelectionStrategy`

```{autodoc2-docstring} src.policies.mandatory_selection.selection_dispatcher_portfolio.PortfolioDispatcher
```

```{rubric} Initialization
```

```{autodoc2-docstring} src.policies.mandatory_selection.selection_dispatcher_portfolio.PortfolioDispatcher.__init__
```

````{py:method} select_bins(context: logic.src.interfaces.context.SelectionContext) -> typing.Tuple[typing.List[int], logic.src.interfaces.context.SearchContext]
:canonical: src.policies.mandatory_selection.selection_dispatcher_portfolio.PortfolioDispatcher.select_bins

```{autodoc2-docstring} src.policies.mandatory_selection.selection_dispatcher_portfolio.PortfolioDispatcher.select_bins
```

````

`````
