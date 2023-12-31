# Cancer Prediction with Lifestyle Factors

This project aims to develop a predictive model for cancer level based on lifestyle factors. 

### Factors Included in Processing

| Factor | Description |
|---|---|
| Age | Age of the individual |
| Gender | Gender of the individual |
| Air Pollution | Exposure to air pollution |
| Alcohol use | Alcohol consumption |
| Dust Allergy | Presence of dust allergy |
| Occupational Hazards | Exposure to occupational hazards |
| Genetic Risk | Family history of cancer |
| Chronic Lung Disease | Pre-existing chronic lung disease |
| Balanced Diet | Adherence to a balanced diet |
| Obesity | Body mass index (BMI) |
| Smoking | Smoking habits |
| Passive Smoker | Exposure to secondhand smoke |
| Chest Pain | Experience of chest pain |
| Coughing of Blood | Coughing up blood |
| Fatigue | Persistent fatigue |
| Weight Loss | Unexplained weight loss |
| Shortness of Breath | Difficulty breathing |
| Wheezing | Wheezing sound while breathing |
| Swallowing Difficulty | Difficulty swallowing |
| Clubbing of Finger Nails | Clubbing of fingernails |
| Frequent Cold | Frequent occurrence of colds |
| Dry Cough | Dry cough that persists for several weeks |
| Snoring | Habitual snoring |


The project was implemented using Jupyter Notebook and is divided into three phases:

## Phase 1: Data Preprocessing

### Tasks

1. Import necessary libraries
2. Load the dataset
3. Handle missing values
4. Identify and remove outliers for numerical data
5. Perform data reduction if necessary
6. Convert numerical data to categorical data if necessary
7. Conduct a series of statistical comparisons based on the dataset

<table>
  <tr>
    <td align="center">
      <img src="histogram_data_distribution.png" alt="histogram_data_distribution" width="400">
      <br>
      Histogram data distribution
    </td>
    <td align="center">
      <img src="level_distribution_age.png" alt="level_distribution_age" width="400">
      <br>
      Level distribution age
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="box_plot_all_datas_befor_drop.png" alt="box_plot_all_datas_befor_drop" width="400">
      <br>
      Boxplot all datas before drop
    </td>
    <td align="center">
      <img src="box_plot_all_datas_after_drop.png" alt="box_plot_all_datas_after_drop" width="400">
      <br>
      Boxplot all datas after drop
    </td>
  </tr>
</table>
  

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
3. Perform clustering on the dataset using appropriate algorithms
4. Implement classification based on the defined classification problem for each group
5. Evaluate the performance of the classification model
6. Reserve a portion of the dataset for testing the implemented classification

## Requirements

* Jupyter Notebook
* Python
* scikit-learn
  
## Usage

* Execute the Jupyter Notebook cells to perform data preprocessing, feature extraction, model training, and evaluation.

## Project Authors

- [Sajjad Shaffaf](https://github.com/sajad002)
- [Jawad Moqaddam](https://github.com/JavadMoghaddam)

## Contributing

Contributions are welcome! Please fork the repository, make your changes, and create a pull request.
