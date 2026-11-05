# ASSA 2026 Autumn School: Sound Field Decomposition Using Transducer Arrays

This repository contains the exercises for the lecture *Sound field decomposition using transducer arrays* at the [ASSA 2026 Autumn School Series in Acoustics](https://assaeindhoven.org/).

## Exercises

- **Exercise 1**: Near-field acoustic holography and the wavenumber transform
  - `exercise1.ipynb`: notebook with solutions [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/samuel-verburg/ASSA-2026-sound-field/blob/main/exercise1.ipynb)
  - `exercise1_student.ipynb`: student version [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/samuel-verburg/ASSA-2026-sound-field/blob/main/exercise1_student.ipynb)

- **Exercise 2**: Wave expansions and regularisation
  - `exercise2.ipynb`: notebook with solutions [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/samuel-verburg/ASSA-2026-sound-field/blob/main/exercise2.ipynb)
  - `exercise2_student.ipynb`: student version [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/samuel-verburg/ASSA-2026-sound-field/blob/main/exercise2_student.ipynb)

## Getting started

The easiest way is to open the notebooks in Google Colab with the buttons above. Nothing needs to be installed.

To run them locally, clone the repository and install `numpy`, `matplotlib` and `cvxpy` (needed for Exercise 2):

```bash
git clone https://github.com/samuel-verburg/ASSA-2026-sound-field.git
cd ASSA-2026-sound-field
pip install numpy matplotlib cvxpy jupyter
```

## License

This project is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

## Acknowledgments

We thank the organizers of the Autumn School Series in Acoustics (ASSA 2026) at Eindhoven University of Technology.

Exercise 1 is adapted from material for the DTU course 34860 Advanced Acoustics by Efren Fernandez Grande and Samuel Verburg.

Exercise 2 is adapted from the [EAA Summer School 2025](https://github.com/samuel-verburg/EAA-summer-school-2025) material by Samuel Verburg, Efren Fernandez Grande and Antonio Figueroa Duran.

All contributors and instructors involved in developing these materials: Melanie Nolan and Samuel Verburg.