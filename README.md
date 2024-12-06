# Efficient Trading with Price Impact: Replication Code (Under Construction)

This repository replicates key components of the paper **"Efficient Trading with Price Impact"** by Xavier Brokmann, Lukas Gonon, Guangyi He, David Itkin, and Johannes Muhle-Karbe (2024). The paper investigates optimal trading strategies that balance expected returns, risk, and trading costs due to price impact, focusing on both linear feedback policies and neural network-based methods for trading under nonlinear impact dynamics.

### Reference
Brokmann, X., Gonon, L., He, G., Itkin, D., & Muhle-Karbe, J. (2024). *Efficient Trading with Price Impact*. SSRN. [Link to paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5014119).

### Contents
The repository includes:
- Python implementations of the linear feedback strategy under the paper's proposed framework.
- Code for performance comparison between linear policies and neural network-based strategies.
- Replication of numerical case studies including parameter calibration, Sharpe ratio evaluation, and robustness checks with alternative decay kernels (e.g., exponential, power-law).

### Key Features
- **Price Impact Models**: Simulates trading scenarios incorporating nonlinear price impact and multi-timescale decay kernels.
- **Optimization Framework**: Demonstrates both analytical solutions (linear models) and numerical approaches (neural networks).
- **Performance Analysis**: Evaluates strategies using metrics like net Sharpe ratio and trading cost sensitivity.

### Requirements
- Python 3.8+
- Libraries: NumPy, SciPy, Matplotlib, TensorFlow/PyTorch (for neural networks)

### Usage
1. Clone the repository: `git clone <repository_url>`
2. Follow the step-by-step instructions in the provided Jupyter notebooks to replicate the results.

For further details, refer to the comments and documentation in the code.
