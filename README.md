# What's Under the Hood?

**The mathematics, optimisation and numerical methods behind machine-learning algorithms.**

This repository accompanies the LinkedIn newsletter **What's Under the Hood?** Each release takes a familiar machine-learning method and opens the black box: the objective function, derivation, geometry, numerical method, implementation details and the conditions under which the method can fail.

The aim is simple: move from calling `fit()` and `predict()` to understanding what those calls actually compute.

## What each lecture contains

A typical lecture includes:

- the modelling problem and assumptions;
- the mathematical formulation;
- the main derivation or optimisation argument;
- numerical and implementation details;
- a worked example with code;
- practical failure modes and diagnostics.

The emphasis is on the connection between mathematics and implementation rather than API syntax alone.

## Lectures

Lectures are added to this repository only when they are published in the LinkedIn series. Unreleased teaching material remains private.

Each published lecture will have a permanent web page under:

```text
lectures/<number>-<topic>/
```

For example:

```text
lectures/01-linear-regression/
```

## Repository structure

```text
.
├── index.html              # GitHub Pages landing page
├── assets/                 # Shared styling and images
├── lectures/               # Publicly released lectures only
├── README.md
└── LICENSE
```

## LinkedIn series

**What's Under the Hood?** is published weekly on LinkedIn. The newsletter gives the concise lecture narrative; this repository provides the fuller technical treatment, derivations and executable examples.

## Licence

This repository is released under the MIT License unless a file states otherwise.

---

**Dr. Muhammad Shoaib**  
Data Scientist | Applied AI, Mathematics & Decision Systems
