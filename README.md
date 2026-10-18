# Formula 1 Podium Prediction (ACL_Team70)

CSEN903 Advanced Computer Lab, Milestone 1.

We predict whether a driver finishes on the podium (top 3) using only information known before the race starts (after qualifying). We also answer three data questions about F1 races.

## Team

| Name | Student ID | Tutorial |
|---|---|---|
| Ahmed Mohamed Abdelkhalek | 58-3594 | T05 |
| Yousef Shawky | 58-8277 | T11 |
| Amr Amin Koura | 58-3669 | T28 |
| Ahmed Yasser Elsawi | 58-2053 | T08 |

## What is in this repo

| File / folder | What it is |
|---|---|
| `milestone1.ipynb` | The full project: cleaning, data questions, features, models, explainability |
| `f1_dataset/` | The 14 F1 CSV tables (Ergast data) used by the notebook |
| `output/pdf/ACL_Team70_Milestone1_Report.pdf` | The written report |
| `requirements.txt` | Python packages needed to run the notebook |

## How to run it

**Option 1: Kaggle (easiest)**

Open our Kaggle notebook: https://www.kaggle.com/code/amrokoura/acl-team70 and click **Run All**. The notebook finds the dataset inside `/kaggle/input/` by itself.

**Option 2: On your own computer**

You need **Python 3.12**. TensorFlow does not support newer versions yet.

1. Clone the repo and go into the folder:
   ```
   git clone https://github.com/AmrKoura/ACL-project.git
   cd ACL-project
   ```
2. Make a virtual environment and turn it on:
   ```
   python -m venv .venv
   .venv\Scripts\activate        (Windows)
   source .venv/bin/activate     (Mac / Linux)
   ```
3. Install the packages:
   ```
   pip install -r requirements.txt
   ```
4. Open `milestone1.ipynb` in VS Code or Jupyter, pick the `.venv` kernel, and click **Run All**.

The notebook reads the data from the `f1_dataset/` folder, so keep that folder next to the notebook.
