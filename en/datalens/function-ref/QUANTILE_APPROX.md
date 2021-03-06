---
editable: false
---

# QUANTILE_APPROX

_Aggregate functions_

#### Syntax {#syntax}


```
QUANTILE_APPROX( value, quant )
```

#### Description {#description}
Returns the approximate `value`-level quantile (`value` should be in range from 0 to 1).

**Argument types:**
- `value` — `Number`
- `quant` — `Number`


**Return type**: Same type as (`value`, `quant`)

{% note info %}

Arguments (`value`, `quant`) must be of the same type.

{% endnote %}


#### Data source support {#data-source-support}

`Materialized Dataset`, `ClickHouse 1.1`.
