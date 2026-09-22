# ADS310 Assignment 1 Sample Page

This is a static, GitHub Pages-ready teaching source for Assignment 1 in ADS310: Research Methods and Data Analytics.

## Teaching purpose

Students transform the supplied evidence into a 2–3 page LaTeX mini report. The task sits between:

- the Week 5 reproduction exercise, which practises basic LaTeX commands; and
- Assignment 2, in which students conduct their own descriptive analysis.

Assignment 1 is a controlled reporting exercise. Students summarize and reorganize supplied material, recreate a table, insert a provided figure, typeset an equation, cross-reference elements, and cite sources. They do not locate or analyse a new dataset.

The page recommends a compact four-part report structure: introduction; total fertility rate and the global trend; discussion; and conclusion. References follow as an unnumbered list. This keeps a 2–3 page report from becoming too fragmented.

The assignment brief also directs students to follow the AI-use and academic-honesty requirements stated in the course outline.

## Files

- `index.html`: teaching article and assignment brief
- `styles.css`: responsive and print styling
- `assets/TFR.png`: supplied Our World in Data figure

## Figure

The page currently uses:

```text
assets/TFR.png
```

The figure is based on the Our World in Data chart:

https://ourworldindata.org/grapher/children-born-per-woman?country=OWID_WRL

Underlying sources listed by Our World in Data are the Human Fertility Database (2025) and UN World Population Prospects (2024).

To replace the image, export the chart as a PNG from Our World in Data and overwrite `assets/TFR.png`. Keep the same filename to avoid changing the HTML.

## Historical table

The page reproduces the table “Age of Marriage of Women and Marital Fertility in Europe before 1790” from Max Roser’s article. The article attributes the data to Gregory Clark (2007), *A Farewell to Alms*.

## Formulae

The page provides:

- conceptual TFR notation based on five-year age-specific fertility groups; and
- percentage change between the stated 1965 and 2023 global values.

Formulae are rendered using MathJax from jsDelivr. If the page must work fully offline, download MathJax locally or replace the rendered formulae with static equation images.

## Main source

Roser, M. (2014). “The global decline of the fertility rate.” *Our World in Data*.

https://ourworldindata.org/global-decline-fertility-rate
