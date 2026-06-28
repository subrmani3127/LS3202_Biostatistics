# LS3202 Biostatistics -- Question Papers & Solutions

This repository contains question papers and fully worked solutions for **LS3202 (Biostatistics)**, organized by year. It was compiled by a former Teaching Assistant for the course, for the benefit of future students.

## How this is organized

```
LS3202_Biostatistics/
├── 2022/
│   ├── question_papers/      <- scanned original question papers (images)
│   └── solutions/            <- solved .tex source + compiled .pdf
├── 2024/
│   ├── question_papers/
│   └── solutions/
├── 2025/
│   ├── question_papers/
│   └── solutions/
└── README.md                 <- this file
```

Each year folder has its own `README.md` describing exactly what is and isn't available for that year (some scans are incomplete -- see below).

## What's available, year by year

| Year | MidSem | End-Sem |
|------|--------|---------|
| 2022 | Complete (Q1-Q8) | Complete (Q1-Q7) |
| 2024 | Complete (Q1-Q7) | **Partial** -- Q1, Q2, Q4 complete; Q3(a)/(b) missing (only Q3(c) survives); Q5 missing entirely |
| 2025 | *Not available* (no scan was found/uploaded) | Complete (Q1-Q5) |

If you are a student or instructor with access to any of the missing pages (2024 End-Sem Q3 a/b, Q5; or any 2025 MidSem paper), **please contribute them** -- see "How to contribute" below.

## How to use the solutions

Each exam's solution is provided as both:
- A `.tex` file (LaTeX source) -- if you want to edit, extend, or repurpose the solutions.
- A compiled `.pdf` -- ready to read directly.

The solutions are written to be **self-contained study material**: each question is restated, followed by a clearly worked solution with all formulae, intermediate steps, and a final boxed answer, in the same spirit as how the instructors expected answers to be presented in the exam itself (hypotheses stated, test choice justified, tail/significance level specified, and an inference/conclusion given).

## Compiling the LaTeX yourself

All `.tex` files use only standard packages (`amsmath`, `amssymb`, `tcolorbox`, `booktabs`, `enumitem`, `fancyhdr`, `hyperref`, and `pgfplots` in one file) and compile cleanly with a standard `pdflatex` installation (e.g., TeX Live):

```bash
pdflatex filename.tex
pdflatex filename.tex   # run twice for table of contents/cross-references
```

## A note on accuracy

These solutions were worked through carefully and cross-checked numerically, but they are **not official answer keys** from the course instructors. If you spot an error, please open an issue or pull request.

## How to contribute

Found a mistake, or have a missing question paper / page? Pull requests and issues are welcome. Please keep the existing folder structure (`<year>/question_papers/` and `<year>/solutions/`) when adding new material.
