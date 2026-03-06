# Multimodal Sequential Recommendation System (Research Project)

This repository contains the source code for the Master's Independent Study: **"Multimodal Sequential Recommendation"**. The project explores the integration of visual modalities (images) into sequential recommendation systems using the Amazon Luxury Beauty dataset.

```text
.
├── notebooks/          # Jupyter Notebooks for experiments
│   ├── 01_Data_Inspection.ipynb    # Data feasibility check
│   └── 02_Data_Statistics.ipynb    # Data distribution & sparsity analysis
├── src/                # Python source code (modules)
├── README.md           # Project documentation
└── requirements.txt    # Python dependencies
```

## 🚀 How to Run

### 1. Prerequisites
Ensure you have Python 3.8+ installed. Install the required libraries:
```bash
pip install -r requirements.txt
```

### 2. Dataset Setup (Crucial Step!)
Due to GitHub's file size limits, the dataset is not included in this repository. 

1. Download the Luxury Beauty dataset (5-core or Raw) and Metadata from the [Amazon Review Data (2018) website](https://nijianmo.github.io/amazon/index.html).
2. Create a folder named `data/` in the root directory.
3. Place the `.json.gz` files inside:
   * `data/Luxury_Beauty.json.gz`
   * `data/meta_Luxury_Beauty.json.gz`

### 3. Running the Notebooks
Navigate to the `notebooks/` directory and launch Jupyter Lab/Notebook:
```bash
jupyter lab
```
Or open the notebooks directly via Google Colab for GPU acceleration.