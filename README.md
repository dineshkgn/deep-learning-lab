# Deep Learning Lab (PyTorch)

Reproducible experiments focused on advanced deep learning with practical evaluation:
- Tabular deep learning (embeddings + attention)
- Optimization + regularization studies
- Ablations and benchmark harness
- Clean experiment tracking and repeatable runs

## Structure
- `experiments/` – runnable experiments
- `src/` – reusable training/eval code
- `configs/` – experiment configs
- `results/` – metrics + plots

## Run
```bash
pip install -r requirements.txt
python -m experiments.train_baseline
