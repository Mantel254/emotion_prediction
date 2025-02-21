# Emotion Clustering using KMeans

## Overview
This project performs emotion analysis and clustering on text data using the following approach:
- **Emotion Analysis:** Utilizes the Hugging Face Transformers pipeline with the `j-hartmann/emotion-english-distilroberta-base` model for text classification.
- **Feature Extraction:** Converts emotion scores into vectors.
- **Clustering:** Groups texts into clusters using the KMeans algorithm from scikit-learn.

## Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python Packages:
  - pandas
  - scikit-learn
  - transformers (Hugging Face)

## Installation
1. Clone this repository:
    ```sh
    git clone https://github.com/Mantel254/emotion_prediction.git
    cd emotion_prediction
    ```

2. Install the required Python packages:
    ```sh
    pip install pandas scikit-learn transformers jupyter
    ```

## Usage
1. Launch Jupyter Notebook:
    ```sh
    jupyter notebook
    ```

2. Open the `main1.ipynb` file in your browser.

3. Ensure the `training.csv` file is present in the same directory as the notebook.

4. Run the notebook cells to:
    - Load and preprocess the text data.
    - Perform emotion classification using the Hugging Face model.
    - Cluster the emotion vectors using KMeans.
    - View the clustered results.

## Results
The notebook displays the clustered data with emotion vectors and their corresponding cluster labels.

## Acknowledgements
- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [scikit-learn](https://scikit-learn.org/)
- [Pandas](https://pandas.pydata.org/)
- [Jupyter Notebook](https://jupyter.org/)
