# Chest X-Ray Classification with Deep Learning

A notebook-based computer-vision project exploring classification of chest X-ray images into health/disease categories using a convolutional neural network workflow.

> **Important:** This is an educational ML project, not a medical device. Predictions must not be used for diagnosis or treatment decisions.

## Project goals

- Load and inspect chest X-ray image data.
- Prepare images for model training.
- Train and evaluate a deep-learning image classifier.
- Explore how computer vision can support medical-image research.

## Repository contents

- `X-Ray Classification.ipynb` — end-to-end experiment and model workflow.

## Tech stack

- Python
- Jupyter Notebook
- Deep learning / CNNs
- Image preprocessing and evaluation

## Getting started

1. Clone this repository:
   ```bash
   git clone https://github.com/B23BB1046/X-Ray-Classification.git
   cd X-Ray-Classification
   ```
2. Open `X-Ray Classification.ipynb` in Jupyter Notebook or Google Colab.
3. Install any missing packages when prompted by the notebook.
4. Configure the dataset path in the notebook to match your local dataset.
5. Run the cells in order and inspect the evaluation outputs.

## Reproducibility notes

The notebook expects an image dataset to be available locally or through a mounted Colab drive. Dataset source, class labels, split strategy, and evaluation metrics should be verified from the notebook before comparing results.

## Future improvements

- Add a pinned dependency file and a documented dataset source.
- Report per-class precision, recall, F1-score, and a confusion matrix.
- Use patient-level splits where applicable to reduce data leakage.
- Add example predictions and limitations to the documentation.

## Disclaimer

This project is for learning and research only and is not validated for clinical use.
