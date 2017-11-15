# ggplot2 (Grammer of graphics) notes
---

### Qplot
Qplot (quick plot) function is the simplest form of plot in ggplot2 package.

```
Syntax: qplot(x, y, data=, color=, shape=, size=, alpha=, geom=, method=, formula=,
facets=, xlim=, ylim=, xlab=, ylab=, main=, sub=)
```

> Example 1: `qplot(x=col1, y=count, color='col1', geom=c("point", "smooth"), method = "lm", xlab="x-axis", main="Title")`

> Example 2: `qplot(color, price / carat, data = diamonds, geom = "jitter", alpha = I(1 / 5), facets = color ~ .) + scale_y_continuous("carat")`

### ggplot
`library(ggplot)`

