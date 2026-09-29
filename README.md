# CMRM Virtual Rhythm Lab v1

A merged and expanded teaching laboratory for Chapter 3 of *Computer Music Representations and Models*.

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

Install Python 3 plus `numpy`, `scipy`, `matplotlib`, `jupyter`, then open the notebooks in Jupyter. The notebooks are intentionally self-contained so they can later be placed on GitHub and opened in Google Colab.

## Interactive Polymetric Visualizer

The browser-based **Polymetric Visualizer** used in Chapter 3 is available directly at:

<https://augusto-sarti.github.io/CMRM-Virtual-Rhythm-Lab/polymetric-visualizer/>

It runs in a modern browser with no installation and no GitHub account. A self-contained offline copy is also included in this package at `interactive/polymetric-visualizer/index.html`; double-click that file to run it locally.

## Provenance

The rhythm-analysis line and synthetic *Sound of Muzak* material are based on work developed by Bruno Di Giorgi during his PhD at Politecnico di Milano. Bruno has given permission for this material to be reused and modernized for the CMRM project. The APM influence-set geometry and associated pedagogical demonstrations are based on material developed by Riccardo Gianpiccolo. The present notebooks are new pedagogical syntheses and modern reimplementations.

## Copyright note

No commercial Porcupine Tree recording is included. The notebook links to an external YouTube reference and generates a synthetic drum reconstruction locally.

## Public release

Before publishing the repository, add the final agreed open-source license and `CITATION.cff`.
