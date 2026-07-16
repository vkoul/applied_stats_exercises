# Stanford STATS 191: Introduction to Applied Statistics — Quarto Book

A Quarto book compiling assignments from Stanford's STATS 191 course into a structured, self-study workbook covering two-sample tests, simple and multiple linear regression, model selection, logistic regression, and a capstone housing-price prediction project.

## Structure

Each chapter follows a three-file pattern:

- **Key Ideas** — intuitive explanations of the core concepts
- **Questions** — the original assignment problems
- **Solutions** — starter code and space to work through answers

## Building

```bash
quarto render
```

Output goes to `docs/` (configured for GitHub Pages).

## Prerequisites

- [Quarto](https://quarto.org/) (>= 1.3)
- R with packages: `ISLR2`, `leaps`, `ggplot2`

## Disclaimer

This repository is an independent study aid created for personal educational use. The assignment content is derived from Stanford University's STATS 191 course (Spring 2024). This project is not affiliated with, endorsed by, or officially connected to Stanford University or its instructors. All original course materials remain the intellectual property of their respective authors.

If you are a current student, please follow your institution's academic integrity policies.
