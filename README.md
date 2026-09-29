# What's Under the Hood?

<p align="center">
  <img src="assets/series-logo.svg" alt="What's Under the Hood?" width="260">
</p>

A weekly series on the mathematics, optimisation and numerical methods behind machine-learning algorithms.

This repository contains the public technical material that accompanies the LinkedIn newsletter **What's Under the Hood?**. Each lecture starts from a familiar machine-learning API and works down to the objective function, geometry, numerical method and implementation choices underneath it.

## What this series is about

Modern libraries make sophisticated methods available through a few lines of code. That is useful, but it can hide the part that matters when models behave unexpectedly: what is actually being solved, which assumptions enter, how the computation is carried out, and where the method can fail.

The emphasis here is on:

- mathematical formulation and derivation;
- optimisation and numerical linear algebra;
- algorithmic mechanics;
- worked numerical examples;
- implementation details and failure modes;
- concise, reproducible Python code.

The aim is to understand what happens between `fit()` and `predict()`.

## Lectures

Lectures are released one at a time alongside the LinkedIn newsletter. Only published material appears in this repository.

| # | Topic | Central question | Status |
|---:|---|---|---|
| 01 | Linear Regression | What does `fit()` actually solve? | Coming first |

## Repository structure

Each released lecture will live in its own directory:

```text
whats-under-the-hood/
├── 01-linear-regression/
│   ├── index.html
│   └── assets/
├── 02-logistic-regression/
│   ├── index.html
│   └── assets/
├── assets/
├── index.html
└── README.md
```

The root `index.html` is the landing page for the series. Individual lecture directories are self-contained so that each release can be read directly through GitHub Pages.

## Publication model

The full teaching archive is maintained privately. Public lectures are adapted and released here one at a time. This keeps the repository aligned with the LinkedIn series rather than exposing the complete course in advance.

## Author

**Dr. Muhammad Shoaib**  
Data Scientist · Applied Mathematics · AI

## Licence

Code and repository material are released under the [MIT License](LICENSE), unless a lecture states otherwise.
