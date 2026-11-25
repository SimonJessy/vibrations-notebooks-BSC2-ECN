# Vibrations – companion notebooks (BSc 2, Centrale Nantes)

Interactive notebooks with animations for the tutorials of the *Vibrations* course
(Bachelor of Science in Engineering, 2nd year, Centrale Nantes).
They run directly in the browser (computer, tablet or phone) with [JupyterLite](https://jupyterlite.readthedocs.io): nothing to install.

➡️ **https://simonjessy.github.io/vibrations-notebooks-BSC2-ECN/**

| Tutorial | Notebook | Statement |
|---|---|---|
| 1 – Free vibration of a 1-DoF system (undamped) | [TD1-freeUndamped](https://simonjessy.github.io/vibrations-notebooks-BSC2-ECN/notebooks/index.html?path=TD1-freeUndamped.ipynb) | [PDF](content/statements/TD1-freeUndamped.pdf) |
| 2 – Free vibration of a 1-DoF system (damped) | [TD2-freeDamped](https://simonjessy.github.io/vibrations-notebooks-BSC2-ECN/notebooks/index.html?path=TD2-freeDamped.ipynb) | [PDF](content/statements/TD2-freeDamped.pdf) |
| 3 – Forced vibration of a 1-DoF system | [TD3-forced](https://simonjessy.github.io/vibrations-notebooks-BSC2-ECN/notebooks/index.html?path=TD3-forced.ipynb) | [PDF](content/statements/TD3-forced.pdf) |
| 4 – Free vibration of an N-DoF system (undamped) | [TD4-freeUndamped](https://simonjessy.github.io/vibrations-notebooks-BSC2-ECN/notebooks/index.html?path=TD4-freeUndamped.ipynb) | [PDF](content/statements/TD4-freeUndamped.pdf) |
| 5 – Forced vibration of an N-DoF system | [TD5-forced](https://simonjessy.github.io/vibrations-notebooks-BSC2-ECN/notebooks/index.html?path=TD5-forced.ipynb) | [PDF](content/statements/TD5-forced.pdf) |

## Lecture notebooks

| Chapter | Notebook |
|---|---|
| 3 – Modal analysis | [Lecture3-modalAnalysis](https://simonjessy.github.io/vibrations-notebooks-BSC2-ECN/notebooks/index.html?path=Lecture3-modalAnalysis.ipynb) |

## How to use

1. Open the link of the tutorial (or scan the QR code printed on the statement).
2. Run all the cells (menu *Run → Run All Cells*); the first run takes a few seconds (Python loads in the browser).
3. Change the parameters with the sliders below each figure and press *Play*.

Changes you make are stored in your browser only.

## Technical notes

Site built with the [jupyterlite/demo](https://github.com/jupyterlite/demo) template and deployed by GitHub Actions on every push to `main`.
Notebooks and statements are in `content/`.
