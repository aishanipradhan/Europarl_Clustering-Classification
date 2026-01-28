# Project Overview

This project explores linguistic similarity and language identification in European languages using proceedings from the Europarl corpus.
Hierarchical clustering and supervised classification are performed in R to examine how closely related languages group together and how accurately they can be distinguished at the sentence level.

Clustering: Unsupervised hierarchical clustering based on cosine distance over language-level text representations

Classification: Supervised language identification using FastText, evaluated via confusion matrices and standard classification metrics

All analyses and figures are generated from a Quarto (.qmd) document, with results rendered to PDF.

## Data

The analysis uses a cleaned subset of the Europarl corpus containing parliamentary proceedings in multiple European languages.

Cleaned Europarl data can be found here: 
https://drive.google.com/drive/folders/1MppfNWnHaFMf3Tc-HGtbIiGNVTsdqB98?usp=drive_link

## Repository Contents

final_project.qmd — Quarto source file containing all analysis, figures, and tables

final_project.pdf — Rendered report

fastText/ — FastText binary used for supervised classification
