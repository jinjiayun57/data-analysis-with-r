# Data Analysis with R: selected lessons

Open teaching materials for introductory statistics with R, adapted from
*Data Analysis with R*, an undergraduate course I designed and taught at
Renmin University of China in 2024. The course was open to students from
across the university, from music and journalism to sociology, statistics and
physics.

**Course page:** https://jinjiayun57.github.io/data-analysis-with-r/

## What is here

The [course page](https://jinjiayun57.github.io/data-analysis-with-r/) shows
the full course design: a map of all sixteen sessions with their learning
objectives and topics, the teaching approach, and how students were assessed.
The slides for every session are included as PDFs, and five sessions are
available as complete lessons with code, simulations,
explanations and exercises:

| Session | Lesson | Key ideas |
|---|---|---|
| 5 | Probability and simulation | Law of large numbers, common distributions, the central limit theorem |
| 6 | Parameter estimation and confidence intervals | Repeated sampling, what "95% confidence" means, interval width |
| 7 | Hypothesis testing | Rejection regions, p-values, one- and two-sided tests, Type I error and power by simulation |
| 10 | Correlation and linear regression | Interpretation, diagnostics, polynomial terms, multicollinearity |
| 14 | Logistic regression | Log-odds and odds ratios, predicted probabilities, sensitivity and specificity |

## Approach

Each lesson starts from something students can observe, usually a small
simulation, before introducing the formal idea, and ends with short exercises
that ask students to change the code and reason about the result. R serves
both as a tool for data analysis and as a laboratory for statistical ideas.

## Structure

- `*.Rmd`: lesson sources (R Markdown)
- `slides/`: lecture slides (PDF, LaTeX Beamer)
- `docs/`: rendered website, published with GitHub Pages
- `_site.yml`: site configuration

To rebuild the site:

```r
install.packages(c("rmarkdown", "ggplot2", "RColorBrewer", "MASS", "car"))
rmarkdown::render_site()
```

All data are simulated or come from packages that ship with R (`datasets`,
`MASS`).

## Licence

Text and figures are licensed under
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/); code is licensed
under the MIT License (see `LICENSE`). You are welcome to reuse and adapt the
materials; please credit the source.

The slides in `slides/` are shared for viewing and teaching use with
attribution; they are not covered by the CC BY licence, and any third-party
images in them remain the property of their owners.
