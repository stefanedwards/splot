# lemon 0.2.0.9000

* **TODO:** Create `grobHeight` on gtables.

* `knit_print` functions are removed (without deprecating them) and replaced
  by `lemon_print` and `load_lemon_print` for pushing `lemon_print` into 
  `knit_print.data.frame`, etc.
  `lemon_print` has been extended to also work on tables (i.e. a summary), but
  does not work nicely for cross-tabulation tables.

* **TODO:** Create CITATION file.

* Extend `lemon_print` to work on cross-tabulation tables.

# lemon 0.2.0

* Legend functions (`g_legend`, `grid_arrange_shared_legend`, `reposition_legend`).
  Two first functions provided by Baptiste Auguié and Shaun Jackson.

# lemon 0.1.0

* Capped axis functions (`capped_horisontal`, `capped_vertical`), the flexible
Cartesian coordinates (`coord_capped_cart`, `coord_capped_flip`, 
`coord_flex_cart`, `coord_flex_flip`, `coord_flex_fixed`), and brackets 
(`brackets_horisontal`, `brackets_vertical`).

* Facets that repeat the labels (`facet_rep_grid`, `facet_rep_wrap`).

* `knitr` printing functions (`knit_print.data.frame`, etc.).