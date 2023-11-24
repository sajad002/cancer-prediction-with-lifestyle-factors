# Cancer Prediction with Lifestyle Factors

This project aims to develop a predictive model for cancer level based on lifestyle factors. The project was implemented using Jupyter Notebook and is divided into three phases:

## Phase 1: Data Preprocessing

### Tasks

1. Import necessary libraries
2. Load the dataset
3. Handle missing values
4. Identify and remove outliers for numerical data
5. Perform data reduction if necessary
6. Convert numerical data to categorical data if necessary
7. Perform stemming, lemmatizing, and stop-word removal for text data if necessary
8. Conduct a series of statistical comparisons based on the dataset

## Phase 2: Extracting Frequent Patterns

### Tasks

1. Import necessary libraries
2. Load the clean dataset obtained from Phase 1
3. Extract frequent patterns using mlxtend
4. Analyze and interpret the extracted frequent patterns

## Phase 3: Classification and Clustering

### Tasks

1. Import necessary libraries
2. Load the clean dataset obtained from Phase 1
3. Transform clean text data into vectors using BERT if data is text-based
4. Perform clustering on the dataset using appropriate algorithms
5. Implement classification based on the defined classification problem for each group
6. Evaluate the performance of the classification model
7. Reserve a portion of the dataset for testing the implemented classification

## Requirements

* Jupyter Notebook
* Python
* TensorFlow
* scikit-learn
* nltk (for text preprocessing)
* mlxtend (for frequent pattern mining)
* Hugging Face or sentence-transformers (for BERT text embedding)

## Installation

1. Install the required libraries using pip:
    ```bash
    pip install tensorflow scikit-learn nltk mlxtend
    

2. For Hugging Face or sentence-transformers, follow their respective installation instructions.

3. Launch Jupyter Notebook and open the project's Jupyter Notebook file.

## Usage

1. Execute the Jupyter Notebook cells to perform data preprocessing, feature extraction, model training, and evaluation.

## Contributing

Contributions are welcome! Please fork the repository, make your changes, and create a pull request.

## License

MIT License
