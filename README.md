# Health Innovation Lab (HIL) — Practical Tutorials

## Schedule

| Date | Time | Room | Title | 
|------|------|------|-------|
| 19.10.2026  | 11:00 - 13:00 | A-222  | Data Exploration |
| 22.10.2026  | 11:00 - 13:00 | A-501  | ML Pipeline |

## How to start using this material

You can either run these notebooks in your browser via Google Colab (no
installation needed), or set them up locally on your own machine.

### Option A — Google Colab (recommended)

1. Open [`tutorial_1_exploring_data.ipynb`](tutorial_1_exploring_data.ipynb)
   or [`tutorial_2_ml_pipeline.ipynb`](tutorial_2_ml_pipeline.ipynb) in this
   repository and click the **"Open in Colab"** badge at the top.
2. Sign in with a Google account if prompted.
3. Run the cells from top to bottom (**Shift + Enter** on each, or
   `Runtime → Run all`). The first code cell in each notebook automatically
   fetches the `data/` folder from this repository — nothing to download or
   upload by hand.
4. Nothing you do in your own Colab copy affects this repository or anyone
   else's copy. If you want to keep your edits, use
   `File → Save a copy in Drive`.

### Option B — Running locally

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR-ORG/YOUR-REPO.git
   cd YOUR-REPO
   ```
2. Create the environment (using [conda](https://docs.conda.io/) /
   [Miniforge](https://github.com/conda-forge/miniforge)):
   ```bash
   conda env create -f environment.yml
   conda activate hil_tutorials
   ```
   Don't use conda? `pip install jupyterlab numpy pandas matplotlib seaborn scikit-learn` works too.
3. Start Jupyter:
   ```bash
   jupyter lab
   ```
4. Open `tutorial_1_exploring_data.ipynb` and run the cells from top to
   bottom. Since the `data/` folder is already right next to the notebook
   in this repo, the notebook will skip the Colab-only download step
   automatically and just use it directly.
