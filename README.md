# RSY Mini Challenge HS26

Mini challenge of the module *Recommender Systems (RSY)*, FHNW, autumn semester 2026.

The exercises are in [`MiniChallenge/RSY_MiniChallenge_HS26.ipynb`](MiniChallenge/RSY_MiniChallenge_HS26.ipynb).
The MovieLens dataset `ml-latest-small` is included under `MiniChallenge/Data/ml-latest-small/`.

## Getting started

1. Fork this repository and clone your fork.
2. Create a virtual environment and install the packages you need, e.g.

   ```bash
   cd MiniChallenge
   python3 -m venv .venv
   source .venv/bin/activate          # Windows: .venv\Scripts\activate
   pip install numpy pandas matplotlib seaborn jupyter
   ```

3. Before submitting, pin your environment so that your notebook is reproducible:

   ```bash
   pip freeze > requirements.txt
   ```

Read the *Guidelines for Implementation and Submission* at the top of the notebook carefully.
