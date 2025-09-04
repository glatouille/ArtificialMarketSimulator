# Artificial Market Simulator

This repository provides a minimal implementation of the artificial market generator described in  
**"The Subtle Interplay between Square-root Impact, Order Imbalance & Volatility II: An Artificial Market Generator" (2025).**

The code allows you to:
- **Simulate trade-by-trade order flow and prices** using the generalized propagator model.
- **Reconstruct metaorders from trades** using a proxy mapping procedure, reproducing the square-root impact law.

## Structure
- `notebooks/simulation_demo.ipynb`  
  Contains the simulation function and the metaorder mapping function, with an example run.
- `requirements.txt`  
  List of Python dependencies (NumPy, pandas, matplotlib, etc.).

## Usage
Clone the repository and install dependencies:
```bash
git clone https://github.com/glatouille/ArtificialMarketSimulator.git
cd ArtificialMarketSimulator
pip install -r requirements.txt
