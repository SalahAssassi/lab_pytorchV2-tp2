# lab_pytorchV2-tp2 — Modèles génératifs avec PyTorch (MNIST)

Créer, entraîner, tester et explorer des modèles sur le dataset MNIST :

1. Chargement du dataset MNIST
2. Modèle discriminatif (classifieur MLP) — accuracy test ≈ 97,3 %
3. Auto-encodeur simple (espace latent 2D) — reconstructions, espace latent, interpolation, limites
4. VAE (espace latent 2D) — reconstructions, génération à partir de z ~ N(0, I), exploration de l'espace latent

Notebook : `Modeles_generatifs_pytorch (1).ipynb`

## Installation (UV)

```bash
uv sync
.venv\Scripts\activate      # Windows
source .venv/bin/activate   # Linux / macOS
```

Puis ouvrir le notebook dans VS Code et sélectionner le kernel `.venv` (Python 3.11).
