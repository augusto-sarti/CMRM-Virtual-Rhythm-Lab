# CMRM Virtual Rhythm Lab

A merged and expanded teaching laboratory for Chapter 3 of *Representing and Modelling Music*.

## What is included

- 00 Start Here
- 01 Onset Detection
- 02 Autocorrelation and Periodicity
- 03 APM Anatomy and Cyclostationarity
- 04 Rhythmogram and Tempo Path
- 05 Beat Tracking and Multiple Hypotheses
- 06 Sound of Muzak End-to-End
- 07 Rhythmic Clusters and Transformations

## How to use locally

Install Python 3 plus `numpy`, `scipy`, `matplotlib`, `jupyter`, then open the notebooks in Jupyter. The notebooks are self-contained and can also be opened directly in Google Colab using the links below.

## Interactive Polymetric Visualizer

The browser-based **Polymetric Visualizer** used in Chapter 3 is available directly at:

<https://augusto-sarti.github.io/CMRM-Virtual-Rhythm-Lab/polymetric-visualizer/>

It runs in a modern browser with no installation and no GitHub account. In the GitHub repository, its source lives at `polymetric-visualizer/index.html`. The separately distributed offline teaching ZIP contains the same visualizer under `interactive/polymetric-visualizer/index.html`. Open either local HTML file in a modern browser.

## Open the notebooks in Google Colab

These links open the notebooks from the public `main` branch (and therefore require its corresponding files to be present in the GitHub repository):

- [00 — Start Here](https://colab.research.google.com/github/augusto-sarti/CMRM-Virtual-Rhythm-Lab/blob/main/notebooks/00_Start_Here.ipynb)
- [01 — Onset Detection](https://colab.research.google.com/github/augusto-sarti/CMRM-Virtual-Rhythm-Lab/blob/main/notebooks/01_Onset_Detection.ipynb)
- [02 — Autocorrelation and Periodicity](https://colab.research.google.com/github/augusto-sarti/CMRM-Virtual-Rhythm-Lab/blob/main/notebooks/02_Autocorrelation_and_Periodicity.ipynb)
- [03 — APM Anatomy and Cyclostationarity](https://colab.research.google.com/github/augusto-sarti/CMRM-Virtual-Rhythm-Lab/blob/main/notebooks/03_APM_Anatomy_and_Cyclostationarity.ipynb)
- [04 — Rhythmogram and Tempo Path](https://colab.research.google.com/github/augusto-sarti/CMRM-Virtual-Rhythm-Lab/blob/main/notebooks/04_Rhythmogram_and_Tempo_Path.ipynb)
- [05 — Beat Tracking and Multiple Hypotheses](https://colab.research.google.com/github/augusto-sarti/CMRM-Virtual-Rhythm-Lab/blob/main/notebooks/05_Beat_Tracking_and_Multiple_Hypotheses.ipynb)
- [06 — Sound of Muzak End to End](https://colab.research.google.com/github/augusto-sarti/CMRM-Virtual-Rhythm-Lab/blob/main/notebooks/06_Sound_of_Muzak_End_to_End.ipynb)
- [07 — Rhythmic Clusters and Transformations](https://colab.research.google.com/github/augusto-sarti/CMRM-Virtual-Rhythm-Lab/blob/main/notebooks/07_Rhythmic_Clusters_and_Transformations.ipynb)

## Provenance

The rhythm-analysis line and synthetic *Sound of Muzak* material are based on work developed by Bruno Di Giorgi during his PhD at Politecnico di Milano. Bruno has given permission for this material to be reused and modernized for the CMRM project. The APM influence-set geometry and associated pedagogical demonstrations are based on material developed by Riccardo Gianpiccolo. The present notebooks are new pedagogical syntheses and modern reimplementations.

## Copyright note

No commercial Porcupine Tree recording is included. The notebook links to an external YouTube reference and generates a synthetic drum reconstruction locally.

## Public release

The public GitHub repository includes its `LICENSE` and `CITATION.cff`. These documents should be retained in the online repository even if they are absent from a separately distributed teaching ZIP.
