---
permalink: /tests_R/
title: "Tests_R"
---

```{r}
library(plotly)
```


```{r}
p <- ggplot(data = stops_county, aes(x = pct_black_stopped, y = pct_white_stopped)) +
  geom_point()
```

```{r}
ggplotly(p) 
```

