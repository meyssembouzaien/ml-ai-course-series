# Machine Learning & AI Course Series

English translations of a full introductory Machine Learning / AI course series,
originally written and taught in French by **Meyssem Bouzaien** (M2 IoT and
Intelligent Systems, Faculty of Sciences of Tunis) during the 2025-2026 academic
year.

Each course was built as a LaTeX Beamer slide deck, covering both theory and
hands-on Python/Scikit-learn examples.

## Course Outline

| # | Course | Format | Topics |
|---|--------|--------|--------|
| 01 | [Introduction to AI](01-intro-to-ai/) | Markdown* | History of AI, AI vs ML vs Deep Learning, NLP, Computer Vision, ethics & future trends |
| 02 | [Introduction to Machine Learning](02-intro-to-ml/) | Beamer (.tex) | ML pipeline, features/labels, train/test split, overfitting, bias-variance, cross-validation |
| 03 | [Python for Machine Learning](03-python-for-ml/) | Beamer (.tex) | NumPy, Pandas, correlation, Matplotlib, first Scikit-learn model |
| 04 | [Classification I: KNN & Decision Trees](04-classification-knn-trees/) | Beamer (.tex) | KNN, decision trees, Gini/entropy, confusion matrix, precision/recall/F1 |
| 05 | [Classification II: Complete Course](05-classification-complete/) | Beamer (.tex) | KNN, Trees, Logistic Regression, SVM, Random Forests, model comparison |
| 06 | [Regression](06-regression/) | Beamer (.tex) | Simple/multiple/polynomial regression, MSE/RMSE/MAE/R², Ridge & Lasso |
| 07 | [Clustering](07-clustering/) | Beamer (.tex) | K-Means, hierarchical clustering, DBSCAN, elbow method, silhouette score |

\* *No LaTeX source was available for the Introduction to AI deck — it was
reconstructed as Markdown from the rendered slides. If the original `.tex` file
turns up, it can replace `01-intro-to-ai/intro-to-ai.md`.*

## Course 07 has two versions

- `clustering-full.tex` — the complete lecture (K-Means, Hierarchical, DBSCAN,
  evaluation, exercises).
- `clustering-short.tex` — a condensed intro version covering just the core
  ideas (K-Means + elbow method), useful as a lighter standalone session.

## Compiling the slides

Each `.tex` file is a standalone Beamer presentation. To compile, e.g.:

```bash
pdflatex intro-to-ml.tex
pdflatex intro-to-ml.tex   # run twice for the table of contents / references
```

Requires a standard LaTeX distribution (TeX Live or MiKTeX) with the `beamer`,
`tikz`, `listings`, and `booktabs` packages.

### A note on images

Courses 04, 05, 06, and 07 reference external images (`images/*.png` —
confusion matrices, decision boundaries, workflow diagrams, etc.) that were
generated separately when the original French decks were built. Those image
files were not part of the source text and are **not included** in this repo.
To compile these decks as-is, either:
- add your own `images/` folder with matching filenames, or
- comment out / remove the `\includegraphics{...}` lines for a text-only build.

The two `.tex` files with no image dependencies (`intro-to-ml.tex` and
`python-for-ml.tex`) compile out of the box.

## Notes on the translation

- All slide content, code comments, and print statements were translated from
  French to English.
- Two small fixes were made during translation:
  - The clustering decks originally credited "Malek Bouzaien" on a couple of
    slides (an apparent copy-paste artifact) — corrected to Meyssem Bouzaien
    throughout.
  - Duplicate clustering source files were consolidated into the two versions
    described above.
- LaTeX/TikZ structure, layout, and diagrams are preserved as-is; only the
  visible text was translated.

## License

Feel free to adapt an appropriate open license (e.g. MIT or CC-BY-4.0) here if
you plan to share this repo publicly.
