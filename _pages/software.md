---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

### CRAN Packages
- **[`dtaudit`](https://cran.r-project.org/web/packages/dtaudit/index.html)**
  ><span style="font-size:0.75em">Diagnostic tools for auditing data analysis workflows built on 'data.table'. Provides functions to validate join operations, compare data.tables, filter with diagnostic output, summarize data quality, check primary keys and variable relationships, and diagnose string columns. Designed to help analysts understand and document data transformations.</span>

### Under Development
- **[`tidyaudit`](https://github.com/fpcordeiro/tidyaudit)**
    ><span style="font-size:0.75em">Pipeline audit trails and data diagnostics for the tidyverse. `tidyaudit` captures metadata-only snapshots at each step of a dplyr pipeline, building a structured audit report without storing the data itself. Operation-aware taps enrich snapshots with join match rates, filter drop statistics, and more. The package combines diagnostic tools for interactive development and production-oriented tools.</span>

- **[`choicer`](https://github.com/fpcordeiro/choicer)**
    ><span style="font-size:0.75em">`choicer` provides implementations of discrete-choice models with a focus on economic applications. Computationally intensive likelihoods are written in C++ and exposed for use with generic optimizers. Special care is taken to handle high-dimensional alternative-specific constants efficiently. Currently supports multinomial logit (MNL), mixed logit (MXL), and nested logit (NL); more models will be added.</span>