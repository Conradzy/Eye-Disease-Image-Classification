# Eye Disease Image Classification

Downloads a four-class retinal image dataset from Kaggle and compares three transfer-learning models for eye-disease classification. It includes dataset exploration, augmentation, training, comprehensive metrics, and presentation-ready dashboards.

## Workflow

1. Load Kaggle credentials from Google Drive and download the eye-disease dataset.
2. Discover the class folders and create train, validation, and test generators.
3. Train MobileNetV2, EfficientNetB0, and DenseNet121.
4. Evaluate aggregate and per-class performance.
5. Generate confusion matrices, ROC/PR curves, dashboards, and comparison charts.

## Data Requirements

- Kaggle dataset `gunavenkatdoddi/eye-diseases-classification`.
- A local `kaggle.json` is required at runtime but must never be committed.

Datasets and generated artifacts are not included unless they are embedded directly in the notebook.

## Requirements

- TensorFlow/Keras
- Kaggle CLI
- scikit-learn
- pandas
- NumPy
- Matplotlib
- Seaborn

Install missing packages in your Jupyter or Google Colab environment before running the notebook.

## Running the Notebook

1. Open [`eye.ipynb`](eye.ipynb) in Jupyter Notebook or Google Colab.
2. Place any required data files in the path expected by the notebook.
3. Update local or Google Drive paths where needed.
4. Run the cells from top to bottom.

## Outputs

- Model metrics and classification reports
- Training-curve comparisons
- Confusion matrices
- ROC and precision-recall curves
- Summary dashboard and tables

## Repository Contents

```text
.
|-- README.md
`-- eye.ipynb
```

## Notes

- This repository preserves the analysis as a notebook-first educational project.
- Results may vary with dataset versions, random splits, package versions, and available hardware.
- Review file paths and runtime-specific commands before executing outside Google Colab.
