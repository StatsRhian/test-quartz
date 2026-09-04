---
title: Lists to excel
tags:
  - R
---


```
library(ggplot2)
data("diamonds")
diamonds_split <- dplyr::split(diamonds, diamonds$cut)
writexl::write_xlsx(diamonds_split, path = "diamonds_by_cut.xlsx")
```

- `split()`: Splits the dataset into a list of data frames by cut. The names of the list (Ideal, Premium, etc.) become the sheet names automatically.
- `write_xlsx()`: Takes the list and writes each element to a separate sheet in a single Excel file.

Each sheet will correspond to a different diamond cut (Ideal, Premium, Good, Very Good, Fair).