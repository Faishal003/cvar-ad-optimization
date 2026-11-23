# Risk-Aware Web Advertisement Optimization (CVaR++ V2)

Code and data for the paper *"Risk-Aware Web Advertisement Optimization Using Adaptive CVaR-Based Multi-Armed Bandit Algorithm"*.

## Files

- `final.ipynb`: all algorithms, experiments, and figures
- `dataset.csv`: click log with 10,000 rounds and 10 ads (binary clicks)

## How to run

1. Put `dataset.csv` in the same folder as the notebook.
2. Open `final.ipynb` in Jupyter or Google Colab.
3. Run all cells from top to bottom.

Requirements: Python 3, `numpy`, `pandas`, `scipy`, `matplotlib`.

## Where each result comes from

| Paper result | Notebook section |
|---|---|
| Main comparison with all baselines (Fig. 3) | *Comprehensive comparison with all baselines* |
| 20-run statistics (Figs. 7–8) | *Statistical validation against all baselines* |
| Table II (t, exact p, Cohen's d, 95% CI) | *Exact statistics for Table II* |
| Table III (ablation) | *Ablation study of CVaR++ V2* |
| Regret fits (Fig. 9) | *Empirical verification of regret bounds* |

All experiments use seeds `42 + 123r` for runs `r = 0, ..., 19`. The ablation cell takes about 10–20 minutes on a normal laptop.
