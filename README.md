# PhysicalModels

My solutions to the modeling labs from BYU's Applied and Computational Mathematics Emphasis (ACME), drawn from *Volume 4* of the lab manuals (differential equations, PDEs and optimal control). Each lab is a notebook that pairs the spec's problem statements with my solutions and their output, plus condensed notes on the concepts the lab covers.

| Lab | Volume | Notebook |
|-----|--------|----------|
| Introduction to Matplotlib: 3D Plotting and Animations | Vol. 4* | [Animation/animation.ipynb](Animation/animation.ipynb) |
| Numerical Methods for Initial Value Problems; Harmonic Oscillators | Vol. 4, Lab 1 | [IVP/ivp.ipynb](IVP/ivp.ipynb) |
| Weight change and Predator-Prey Models | Vol. 4, Lab 2 | [WeightLoss/weightloss.ipynb](WeightLoss/weightloss.ipynb) |
| Modelling the spread of an epidemic: SIR models | Vol. 4, Lab 4 | [SIR/sir.ipynb](SIR/sir.ipynb) |
| Lorenz Equations | Vol. 4, Lab 5 | [LorenzEquations/lorenz_equations.ipynb](LorenzEquations/lorenz_equations.ipynb) |
| Bifurcations | Vol. 4, Lab 6 | [Hysteresis/hysteresis.ipynb](Hysteresis/hysteresis.ipynb) |
| The Finite Difference Method | Vol. 4, Lab 7 | [FiniteDifference/finite_difference.ipynb](FiniteDifference/finite_difference.ipynb) |
| Heat Flow | Vol. 4, Lab 8 | [HeatFlow/heat_flow.ipynb](HeatFlow/heat_flow.ipynb) |
| Anisotropic Diffusion | Vol. 4, Lab 9 | [AnisotropicDiffusion/anisotropic_diffusion.ipynb](AnisotropicDiffusion/anisotropic_diffusion.ipynb) |
| Wave Phenomena | Vol. 4, Lab 10 | [WaveEquation/wave_equation.ipynb](WaveEquation/wave_equation.ipynb) |
| Poisson's equation | Vol. 4, Lab 11 | [PoissonEquation/poisson_equation.ipynb](PoissonEquation/poisson_equation.ipynb) |
| The Finite Element method | Vol. 4, Lab 13 | [FiniteElement/finite_element.ipynb](FiniteElement/finite_element.ipynb) |
| Method of Mean Weighted Residuals | Vol. 4, Lab 15 | [Spectral1/spectral1.ipynb](Spectral1/spectral1.ipynb) |
| A Pseudospectral method for periodic functions | Vol. 4, Lab 16 | [Spectral2/spectral2.ipynb](Spectral2/spectral2.ipynb) |
| Transit time crossing a river | Vol. 4, Lab 18 | [RiverCrossing/river_crossing.ipynb](RiverCrossing/river_crossing.ipynb) |
| Inverse Problems | Vol. 4, Lab 19 | [InverseProblem/inverse_problem.ipynb](InverseProblem/inverse_problem.ipynb) |
| Total Variation and Image Processing | Vol. 4, Lab 20 | [TotalVariation/total_variation.ipynb](TotalVariation/total_variation.ipynb) |
| The Inverted Pendulum | Vol. 4, Lab 21 | [InvertedPendulum/inverted_pendulum.ipynb](InvertedPendulum/inverted_pendulum.ipynb) |
| HIV Treatment Using Optimal Control | Vol. 4, Lab 23 | [HIV/hiv.ipynb](HIV/hiv.ipynb) |

\* The course assigned this lab in September 2018; it joined the manual as Lab 1 in the January 2019 edition.

Lab numbers follow the August 2018 edition of Volume 4, the one these labs were written against. Problem statements are quoted from the course's lab notebooks where I had them, which differ in places from the manual, and from that edition otherwise. Most folders also keep the grader feedback from my original submissions (`*_feedback.txt`).

## Running the notebooks

Each notebook runs from its own folder. The images and data each lab uses sit next to its notebook, except `vibration.npz` (73 MB) for the Animation lab's Problem 5: download `vibration.npz.gz` from ACME's [data repository](https://github.com/Foundations-of-Applied-Mathematics/Data/tree/master/Animation) and unzip it in `Animation/`. The notebooks need NumPy, SciPy, Matplotlib and imageio. The Finite Difference and River Crossing labs also need [autograd](https://github.com/HIPS/autograd) (`pip install autograd`). Animations are embedded as interactive HTML, which plays in Jupyter but not in GitHub's notebook viewer; the Lorenz and Animation labs also keep their original 2018 animations as `.mp4` files.

## Credits

The lab specifications come from the [Foundations of Applied Mathematics](https://foundations-of-applied-mathematics.github.io/) *Volume 4* lab manual, © Dr. J. Humpherys, licensed under [CC BY 3.0 US](http://creativecommons.org/licenses/by/3.0/us/). The images and data come from the original lab materials and the project's official [data repository](https://github.com/Foundations-of-Applied-Mathematics/Data). Problem statements are quoted from the specs; the solutions are my own.
