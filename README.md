# Wallet Risk Scoring

This repo contains:
- **`wallet_risk_scoring.ipynb`** — Google Colab notebook that:
  - Fetches on‑chain TX history via Etherscan
  - Computes risk features per wallet
  - Normalizes & aggregates into a 0–1000 score
  - Exports `wallet_risk_scores.csv`

- **`wallet_risk_scores.csv`** — final wallet risk scores.  
  *(Previewed below by GitHub)*

## CSV Preview

![CSV preview](https://raw.githubusercontent.com/abhigyanpal1/wallet-risk-scoring/main/wallet_risk_scores.csv)

## How to run
1. Open the notebook in Colab:  
   https://colab.research.google.com/github/abhigyanpal1/wallet-risk-scoring/blob/main/wallet_risk_scoring.ipynb  
2. Provide your Etherscan key and run all cells.

## Dependencies

- `pandas`
- `requests`
- `scikit-learn`

(You can install via `pip install -r requirements.txt`.)

