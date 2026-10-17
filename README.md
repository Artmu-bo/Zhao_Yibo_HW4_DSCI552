# DSCI 552 Homework 4 – Zhao Yibo

- **Name:** Zhao Yibo
- **GitHub Username:** Artmu-bo
- **USC ID:** 5635641435

## Contents

| Path | Description |
|------|-------------|
| `notebook/Zhao_Yibo_HW4.ipynb` | All code, outputs and written answers for Homework 4 |
| `data/AReM/` | AReM dataset (7 activity folders, 88 instances) from the UCI Machine Learning Repository |
| `requirements.txt` | Python packages and versions used |


## How to run

```bash
pip install -r requirements.txt
cd notebook
jupyter notebook Zhao_Yibo_HW4.ipynb
```

The notebook reads the data from `../data/AReM`, so it must be run from inside the `notebook/` folder.
All random operations use a fixed seed (42), so results are reproducible. Running the whole notebook
takes about 15 minutes, mainly for the cross-validation in 2(a)iii and 2(c)i.
