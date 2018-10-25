README.Rmd
================

[FastBaseR](https://github.com/WinVector/FastBaseR)
===================================================

Examples of fast grouped row-wise operations in R (no C, C++, data.table, or dplyr used).

Timing example [here](https://github.com/WinVector/Examples/blob/master/grouped_ops/grouped_sum_timing.md).

Currently implements:

-   grouped cumulative sum.
-   grouped sum.
-   grouped running maximum.
-   grouped maximum.
-   grouped argmax.

Todo:

-   grouped running NA replacement (extending `zoo::na.locf()`).
