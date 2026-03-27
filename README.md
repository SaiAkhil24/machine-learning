# Tutorial 05 — Contrastive Learning: Learning Representations Without Labels

> **SimCLR on Real STL-10 Photographs**  
> University of Hertfordshire | MLNN Assignment | 2025

---

## What This Tutorial Covers

Contrastive learning (SimCLR) learns visual representations from unlabelled data. Two augmented views of the same image are pulled together in embedding space; different images are pushed apart. With only 10% of labels, SimCLR nearly matches fully supervised training on 100%.

**You will learn:**
- Why data augmentation creates free supervision signals
- The SimCLR framework: augmentation → encoder → projector → NT-Xent loss
- NT-Xent loss derived from scratch
- How temperature τ affects learning dynamics
- Linear evaluation: measuring representation quality without labels
- SSL progress: CPC → SimCLR → DINO → MAE

---

## Files in This Folder

| File | Description |
|------|-------------|
| `contrastive_learning_tutorial.ipynb` | Full Jupyter notebook |
| `contrastive_learning_tutorial.docx` | Word tutorial document |
| `README.md` | This file |
| `LICENSE` | MIT Licence |

---

## How to Run

```bash
pip install numpy matplotlib scipy
jupyter notebook contrastive_learning_tutorial.ipynb
```

> For full SimCLR with ResNet-50, install: `pip install torch torchvision`

---

## Accessibility

- **tab10 palette + distinct marker shapes** for all scatter plots
- **5+ distinct hatch patterns** on all bar charts
- **Architecture diagram** uses colour + text labels (no colour-only encoding)
- **Alt-text captions** for every figure
- **Structured headings** for screen reader navigation

---

## References

1. Chen et al. (2020) SimCLR: https://arxiv.org/abs/2002.05709
2. He et al. (2020) MoCo: https://arxiv.org/abs/1911.05722
3. Chen & He (2021) SimSiam: https://arxiv.org/abs/2011.10566
4. Oord et al. (2018) CPC: https://arxiv.org/abs/1807.03748
5. STL-10: https://cs.stanford.edu/~acoates/stl10

**License:** MIT — **GitHub:** https://github.com/yourusername/ml-tutorials/tree/main/tutorial-05-contrastive-learning
