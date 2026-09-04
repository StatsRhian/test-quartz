---
title: Dates are dates, not numbers
---

I find treating dates as numeric a little confusing in code. 

Especially finacial years.

```
        # TODO: revisit why start year and end year are formatted differently
        choices = c("2023/24" = 202324),
        selected = as.character(
          (default_baseline_year * 100) + ((default_baseline_year + 1) %% 100)
        )
```