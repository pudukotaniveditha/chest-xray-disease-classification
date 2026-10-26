# Explainable Multi-Class Chest X-Ray Disease Classification

This project explores explainable multi-class chest X-ray classification using U-Net lung segmentation, ConvNeXt and RepViT feature extraction, feature fusion, a dense classifier, and Grad-CAM explanations.

## Disease classes
- COVID-19
- Normal
- Viral Pneumonia
- Lung Opacity

## Project files
- `PROJECT.ipynb` — project notebook containing data preparation, model pipeline, and evaluation code.
- `docs/Diagrams/` — PNG diagram previews and editable `.drawio` files for the system architecture, flow chart, logical diagram, behavioural diagram, ER diagram, and DFD Level 0.

## Dataset
The notebook currently refers to the COVID-19 Radiography Database through a Kaggle-specific path. To run the notebook elsewhere, update `DATASET_PATH` in the first cells to the dataset location on your machine or notebook environment. Do not commit the full dataset to GitHub unless you have verified its license and repository storage limits; link to the official dataset source instead.

## Running the notebook
1. Open `PROJECT.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
2. Make sure the required dataset is available in your environment.
3. Update `DATASET_PATH` if needed.
4. Install any missing Python packages shown in the notebook imports.
5. Run the notebook cells in order.

## Diagrams
The `.drawio` files can be opened and edited at https://app.diagrams.net/ using **File → Open From → Device**. PNG files are previews.

## Notes
This repository is for academic/research purposes and is not a substitute for professional medical diagnosis.
