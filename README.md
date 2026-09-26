# CMRM Virtual Rhythm Lab

Interactive notebooks and teaching material for Chapter 3 (Rhythm) of *Computer Music Representations and Models*.

## Run the laboratories in Google Colab

No local Python installation is required. Choose a laboratory below, open it in Colab, and use **Runtime -> Run all** (or execute the cells one at a time).

| Lab | Topic | Open in Colab |
|---|---|---|
| 00 | Start Here | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/augusto-sarti/CMRM-Virtual-Rhythm-Lab/blob/main/notebooks/00_Start_Here.ipynb) |
| 01 | Onset Detection | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/augusto-sarti/CMRM-Virtual-Rhythm-Lab/blob/main/notebooks/01_Onset_Detection.ipynb) |
| 02 | Autocorrelation and Periodicity | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/augusto-sarti/CMRM-Virtual-Rhythm-Lab/blob/main/notebooks/02_Autocorrelation_and_Periodicity.ipynb) |
| 03 | APM Anatomy and Cyclostationarity | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/augusto-sarti/CMRM-Virtual-Rhythm-Lab/blob/main/notebooks/03_APM_Anatomy_and_Cyclostationarity.ipynb) |
| 04 | Rhythmogram and Tempo Path | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/augusto-sarti/CMRM-Virtual-Rhythm-Lab/blob/main/notebooks/04_Rhythmogram_and_Tempo_Path.ipynb) |
| 05 | Beat Tracking and Multiple Hypotheses | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/augusto-sarti/CMRM-Virtual-Rhythm-Lab/blob/main/notebooks/05_Beat_Tracking_and_Multiple_Hypotheses.ipynb) |
| 06 | *Sound of Muzak* End-to-End | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/augusto-sarti/CMRM-Virtual-Rhythm-Lab/blob/main/notebooks/06_Sound_of_Muzak_End_to_End.ipynb) |
| 07 | Rhythmic Clusters and Transformations | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/augusto-sarti/CMRM-Virtual-Rhythm-Lab/blob/main/notebooks/07_Rhythmic_Clusters_and_Transformations.ipynb) |

The recommended starting point is **Lab 00 — Start Here**. The notebooks are arranged as an executable companion to the chapter rather than as independent software demos.

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

Install Python 3 and the packages listed in `requirements.txt`, then open the notebooks in Jupyter. The notebooks are designed to remain self-contained apart from explicitly identified assets.

## Provenance

The rhythm-analysis line, phase-autocorrelation material, rhythmogram/tempo/beat-tracking material, and the synthetic *Sound of Muzak* example are based on work developed by Bruno Di Giorgi during his PhD at Politecnico di Milano. Bruno has given permission for this material to be reused and modernized for the CMRM project.

The APM influence-set geometry and associated pedagogical demonstrations are based on material developed by Riccardo Gianpiccolo.

The notebooks in this repository reorganize and extend these materials for teaching, normalize notation, modernize implementations, and add new controlled experiments and explanatory material.

See `PROVENANCE.md` for details.

## Sound of Muzak audio asset

Lab 6 uses `assets/sound_of_muzak_synthetic.wav`, the synthetic reconstruction produced in Bruno Di Giorgi's original teaching/research material and reused here with permission. The notebook does not redistribute or analyze a commercial Porcupine Tree recording as an included asset.

For listening comparison, the notebook points to an external public reference. The commercial recording is not redistributed in this repository.

## License and citation

The repository is released under the **BSD 3-Clause License**; see `LICENSE`.

Citation metadata are provided in `CITATION.cff`. GitHub can use this file to expose a **Cite this repository** entry on the repository page.
