# ggplot2 (Grammer of graphics) notes
---

### Qplot
Qplot (quick plot) function is the simplest form of plot in ggplot2 package.

```
Syntax: qplot(x, y, data=, color=, shape=, size=, alpha=, geom=, method=, formula=,
facets=, xlim=, ylim=, xlab=, ylab=, main=, sub=)
+ scale_fill_gradient(low="white", high="black")
```

> Example 1: <font color="blue">`qplot(x=col1, y=count, color='col1', geom=c("point", "smooth"), method = "lm", xlab="x-axis", main="Title")`</font>

> Example 2: `qplot(color, price / carat, data = diamonds, geom = "jitter", alpha = I(1 / 5), facets = color ~ .) + scale_y_continuous("carat")`

### ggplot
`library(ggplot)`

Layering of ggplot components:
* Data
* Geometric object (geom)
* Statistical transformation (stat)
* Scales
* Coordinate system, position adjustment, faceting, theme, etc

* coord_flip()
* coord_map()
* coord_polar()

