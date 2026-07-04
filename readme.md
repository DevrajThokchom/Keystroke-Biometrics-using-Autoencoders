# Keystroke Biometrics using Autoencoders

A one-class Variational Autoencoder (VAE) that learns one user's typing rhythm
and flags other typists as impostors, using the CMU Keystroke Dynamics -
Benchmark Data Set.

## Dataset

This project uses the **Keystroke Dynamics - Benchmark Data Set**:
https://www.cs.cmu.edu/~keystroke

Download `DSL-StrongPasswordData.csv` from that page and place it at
`data/DSL-StrongPasswordData.csv`.

## Running locally

1. Create a virtual environment (optional but recommended):

       python3 -m venv .venv
       source .venv/bin/activate      # on Windows: .venv\Scripts\activate

2. Install dependencies:

       pip install -r requirements.txt

3. Launch Jupyter and run the notebook top to bottom:

       jupyter notebook Keystroke_Analysis.ipynb

## Running on Google Colab

Open `Keystroke_Analysis.ipynb` in Colab, upload `DSL-StrongPasswordData.csv`
into a `data/` folder there (or mount Drive and adjust the path in the
notebook), then run all cells.
