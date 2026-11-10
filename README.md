# Lab 07: Decision Trees and Random Forests

<!-- STAT 486 · Fall 2026 -->

## Objective

Fit and interpret classification trees on the Tic-Tac-Toe Endgame data. Compare split criteria, use cross-validation to choose a cost-complexity pruning level, and assess a random forest using held-out accuracy, out-of-bag accuracy, and impurity-based feature importance.

## Before you begin

You need Git, a GitHub account, and [uv](https://docs.astral.sh/uv/getting-started/installation/) installed on your computer.

## Set up your submission repository

### 1. Create your private submission repository

On [`STAT-486-Fall-2026/lab-07`](https://github.com/STAT-486-Fall-2026/lab-07), select **Use this template** and then **Create a new repository**. Set the owner to the `STAT-486-Fall-2026-Labs` organization and name the repository exactly:

```text
lab-07-<netid>
```

For example, a student whose NetID is `jdoe42` must create `lab-07-jdoe42`. Use your institutional NetID even if it differs from your GitHub username. Make the repository **private**, then create it. Do not fork the starter repository.

### 2. Clone your repository

Copy the HTTPS URL for **your repository**, then run the following commands. Replace the NetID placeholder.

```bash
git clone https://github.com/STAT-486-Fall-2026-Labs/lab-07-<netid>.git
cd lab-07-<netid>
```

### 3. Create and lock your environment

The starter includes a lab-specific `pyproject.toml` and `.python-version`. From the repository directory, run:

```bash
uv sync
```

This creates your local `.venv` and generates `uv.lock`. Keep the supplied `pyproject.toml` unchanged unless the lab directions explicitly say otherwise. Commit the generated `uv.lock` with your work, but never commit `.venv`.

### 4. Complete the lab

Open `lab-07.ipynb` in your preferred editor and configure it to use the Python interpreter or notebook kernel in this repository's `.venv`.

Complete all code and written responses in the notebook. The local dataset is `data/tic-tac-toe.csv`; its provenance and checksum are in [`data/README.md`](data/README.md). Use the specified random state and split, keep pruning selection within the training data, and run the completed notebook from top to bottom. Figures and tables should be readable.

### 5. Commit and push your work

```bash
git add lab-07.ipynb uv.lock
git commit -m "Complete Lab 07"
git push
```

## Submission

Paste the root URL of your repository into the Canvas Lab 07 submission textbox:

```text
https://github.com/STAT-486-Fall-2026-Labs/lab-07-<netid>
```

Do not open a pull request and do not upload the notebook file to Canvas.
