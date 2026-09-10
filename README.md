# Machine-Learning Classification Analysis

An academic machine-learning project that explores a passenger dataset, prepares features, trains classification models, and evaluates their performance with accuracy scores and confusion matrices.

## Results

- Random Forest: 83.9% accuracy on the train/test split
- Decision Tree: 95.0% accuracy on a separate labelled evaluation dataset

Results reflect the supplied datasets and experimental setup in the notebook; they should not be interpreted as production performance.

## Models evaluated

- K-Nearest Neighbours
- Random Forest
- Decision Tree

## Workflow

1. Inspect feature distributions and missing values
2. Remove irrelevant attributes
3. Encode categorical variables
4. Split data for training and evaluation
5. Train multiple classifiers
6. Compare accuracy and confusion matrices
7. Apply the selected models to a separate dataset

## Repository structure

- `notebooks/classification_analysis.ipynb` - complete analysis
- `data/traintest.csv` - development dataset
- `data/tested.csv` - labelled evaluation dataset
- `data/predict.csv` - prediction dataset
- `requirements.txt` - Python dependencies

## Running locally

Clone the repository and open a terminal in its root directory.

### Windows PowerShell

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
py -m pip install -r requirements.txt
py -m jupyter notebook notebooks\classification_analysis.ipynb
```

If PowerShell blocks the activation script, permit it for only the current terminal session and activate again:

```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
.\.venv\Scripts\Activate.ps1
```

### macOS or Linux

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
python -m jupyter notebook notebooks/classification_analysis.ipynb
```

When the environment is active, the terminal prompt normally begins with `(.venv)`.

## Technologies

Python, Jupyter, pandas, matplotlib, scikit-learn, data cleaning, classification, model evaluation

## Academic context

Created as an individual Computer Science assignment at Cégep Heritage College and reorganized as a portfolio repository.

## Author

Joshua Mina-Loaiza
