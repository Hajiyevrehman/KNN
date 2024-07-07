# KNN Project

## Overview

This project implements a K-Nearest Neighbors (KNN) algorithm. It includes source code, datasets, and a Jupyter notebook for running and analyzing the KNN implementation.

## File Structure

project_root
├── README.md  (this file)
├── algorithms/  (source code folder)
├── knn.ipynb  (main notebook)
├── get_datasets.py  (dataset download script)
└── datasets/  (datasets folder)

## Getting Started

### Prerequisites

- Python 3.9.5 or later
- Jupyter Notebook

### Setting Up the Environment

1. Clone this repository to your local machine.
2. (Optional) Create a virtual environment:
   python -m venv knn_env
   source knn_env/bin/activate  # On Windows, use `knn_env\Scripts\activate`
3. Install required packages:
   pip install -r requirements.txt

### Preparing Datasets

Before running the notebook, download the required datasets by executing:

python get_datasets.py

This command will download the necessary datasets and place them in the ./datasets directory.

## Running the Project

1. Open the Jupyter Notebook:
   jupyter notebook
2. Navigate to and open knn.ipynb.
3. Run through the cells in the notebook to see the KNN implementation and analysis.

## Implementation Details

The main components of this project are:

1. algorithms/knn.py: Contains the KNN algorithm implementation
2. knn.ipynb: Jupyter notebook for running and visualizing the KNN algorithm

## Usage Tips

- Make sure to run all code cells in the notebook sequentially.
- The notebook includes inline questions and areas for plotting results.
- Modify only the parts of the code that are explicitly marked for editing.

## Troubleshooting

If you encounter package-related issues, try using a conda environment:

1. Install Anaconda or Miniconda
2. Create and activate a new environment:
   conda create -n knn_project python=3.9.5
   conda activate knn_project
3. Install the required packages:
   pip install -r requirements.txt

## Additional Information

### Using Jupyter Notebook

For those new to Jupyter Notebook:

- Notebooks consist of code cells and markdown cells.
- To run a cell, select it and press Ctrl + Enter or click the "Run" button.
- Code cells execute Python code; markdown cells render formatted text.
- Variables and functions defined in one cell are available in subsequent cells.

### Exporting Results

To export the notebook as a PDF:
1. Go to File > Download as > PDF via LaTeX (.pdf)
2. Ensure all cells have been executed before exporting.

## Support

If you have any questions or encounter issues, please open an issue in this repository.