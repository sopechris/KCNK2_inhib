# Bachelor's Thesis: Activity Prediction for Intermediate Conductance Calcium-Activated Potassium Channel Inhibitors using Random Forest.


In this repository, you can find all the materials related to my Bachelor's thesis, completed at Universidad del Pais Vasco (EHU).

## 📄 Contents

- `thesis.pdf`: The final compiled version of the thesis.
- `thesis_tex/`: LaTeX source files used to write the thesis.
- `notebooks/`: Jupyter notebooks used for data analysis and modeling:
  - `Feature_Analysis.ipynb`
  - `Optimization.ipynb`
  - `Model_Evaluation.ipynb`

## 🧠 Overview

The thesis explores how ion channels, located in the membrane of cells, are a great deal when referring to regulation of ion transport in our body. Potassium channel inhibitors play a grand role in the regulation and so-called intermediate conductance of this well-known and mapped channel called SK4. Using machine learning techniques, the inhibitory capacity of any molecule can be addressed by approximation, giving very good results and not having to wait for yearlong biological simulations. This allows to target potentially functional drugs much faster and easier, without that much computer and time expense.

## 🛠️ How to Compile the Thesis

To compile the LaTeX source into a PDF:
```bash
cd thesis_tex
pdflatex thesis.tex
bibtex thesis
pdflatex thesis.tex
pdflatex thesis.tex
