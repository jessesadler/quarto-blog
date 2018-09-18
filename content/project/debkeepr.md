---
author: Jesse Sadler
date: 2018-09-18T14:09:52-07:00
description: "An R package for the analysis of non-decimal historical currencies"
draft: false
title: "debkeepr"
subtitle: "An R package for the analysis of non-decimal historical currencies"
---

[debkeepr](https://jessesadler.github.io/debkeepr) is an R package that provides an interface for working with non-decimal currencies that use the tripartite system of pounds, shillings, and pence. The package includes functions to apply arithmetic and financial operations to single or multiple values and to analyze account books that use either [single-entry bookkeeping](https://en.wikipedia.org/wiki/Single-entry_bookkeeping_system) or [double-entry bookkeeping](https://en.wikipedia.org/wiki/Double-entry_bookkeeping_system) with the latter providing the name for `debkeepr`.

`debkeepr` can be installed from GitHub with [devtools](https://github.com/hadley/devtools). Feedback is always welcome and any bug reports or feature requests can be made on [GitHub](https://github.com/jessesadler/debkeepr/issues).

``` {.r}
# install.packages("devtools")
devtools::install_github("jessesadler/debkeepr")
```

<!--more-->

## Resources
- [debkeepr website](https://jessesadler.github.io/debkeepr)
- [Introducing debkeepr blog post](https://jessesadler.com/post/debkeepr-intro/)
- [Getting Started with debkeepr vignette](https://jessesadler.github.io/debkeepr/articles/debkeepr.html): A more in depth overview of `debkeepr`’s functions and their use in various contexts.
- [Transactions in Richard Dafforne's Journal vignette](https://jessesadler.github.io/debkeepr/articles/transactions.html): Examples of financial and arithmetic calculations dealing with various currencies taken from the example journal in Richard Dafforne’s *Merchant’s Mirrour* (1660).
- [Analysis of Richard Dafforne’s Journal and Ledger vignette](https://jessesadler.github.io/debkeepr/articles/ledger.html): An analysis of the example journal and ledger in Dafforne’s *Merchant’s Mirrour* using the `dafforne_transactions` and `dafforne_accounts` data provided in `debkeepr`.