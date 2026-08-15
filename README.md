## Notebook index

| Notebook | Topic |
|---|---|
| [`ch1.ipynb`](ch1.ipynb) | Combinatorial Foundations for Probability |
| [`ch2.ipynb`](ch2.ipynb) | $\sigma$-Algebras and the Structure of Events |
| [`ch3.ipynb`](ch3.ipynb) | The Concept of Probability |
| [`ch4.ipynb`](ch4.ipynb) | Conditional Probability and Independence |
| [`ch5.ipynb`](ch5.ipynb) | Random Variables |
| [`ch6.ipynb`](ch6.ipynb) | Distribution Functions, Laws and Quantiles |
| [`ch7.ipynb`](ch7.ipynb) | Expectation: Construction and Fundamental Properties |
| [`ch8.ipynb`](ch8.ipynb) | Discrete Distributions and Count Models |
| [`ch9.ipynb`](ch9.ipynb) | Continuous Distributions and Geometric Probability |
| [`ch10.ipynb`](ch10.ipynb) | Important Continuous Distributions |
| [`ch11.ipynb`](ch11.ipynb) | Joint Distributions, Independence and Covariance |
| [`ch12.ipynb`](ch12.ipynb) | Conditional Expectation: Information, Prediction and Variance Decomposition |
| [`ch13.ipynb`](ch13.ipynb) | Moment Generating and Characteristic Functions |
| [`ch14.ipynb`](ch14.ipynb) | Limit Theorems: The Law of Large Numbers and the Central Limit Theorem |
| [`ch15.ipynb`](ch15.ipynb) | Monte Carlo Methods: Simulation, Error and Variance Reduction |
| [`ch16.ipynb`](ch16.ipynb) | Discrete-Time Markov Chains |
| [`ch17.ipynb`](ch17.ipynb) | The Poisson Process |
| [`ch18.ipynb`](ch18.ipynb) | Actuarial Mathematics: Risk, Premiums and Reinsurance |
| [`appendixA.ipynb`](appendixA.ipynb) | Measure Theory and Stieltjes Integration |
| [`appendixB.ipynb`](appendixB.ipynb) | Functions of Several Variables and Multiple Integrals |

## Requirements

The notebooks use Python 3 and a small standard scientific-Python stack:

```text
numpy
matplotlib
ipywidgets
jupyter
```

They also use modules from the Python standard library such as `math`, `random`, `statistics`, `itertools`, `fractions`, `collections`, and `cmath` where needed.

## Run locally

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/Probability-Theory-with-Python-and-AI.git
cd Probability-Theory-with-Python-and-AI
```

Create and activate a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate
```

On Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

Install the dependencies:

```bash
pip install numpy matplotlib ipywidgets jupyter
```

Then start Jupyter Lab:

```bash
jupyter lab
```

Open any notebook and run the cells from top to bottom.

## Run in Google Colab

The notebooks include optional Google Colab widget support. After the repository is public on GitHub, you can open a notebook through Google Colab by selecting **File → Open notebook → GitHub** and entering the repository URL.

No Colab-specific installation is required for the core examples beyond the packages normally available in the Colab environment.

## Recommended order

For a complete progression through the material, work through `ch1.ipynb` to `ch18.ipynb` in numerical order. The appendices can be used as supporting references:

- **Appendix A** develops measure-theoretic and Stieltjes-integration foundations.
- **Appendix B** reviews multivariable functions, regions, and multiple integrals.

Because each notebook contains its own setup and computational examples, individual chapters can also be explored independently when reviewing a specific topic.

## Learning approach

The notebooks are intended to complement, not replace, the mathematical development. A typical workflow is:

1. Study the definition, theorem, or derivation.
2. Run the corresponding computational example.
3. Change parameters using the interactive controls.
4. Compare simulation with the theoretical result.
5. Use the code as a starting point for further experiments.

This approach helps connect rigorous probability theory with intuition, computation, and reproducible experimentation.

## Repository structure

```text
.
├── ch1.ipynb
├── ch2.ipynb
├── ...
├── ch18.ipynb
├── appendixA.ipynb
├── appendixB.ipynb
└── README.md
```

## About the project

*Probability Theory with Python and AI* develops probability from foundational ideas to advanced topics while using Python as a computational companion. These notebooks provide the experimental layer of that project: visual demonstrations, simulations, numerical checks, and interactive exploration alongside the theory.

---

If you find these notebooks useful, consider starring the repository on GitHub.
