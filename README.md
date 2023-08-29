# House Sales Prediction in King County, USA

This project is focused on predicting house sale prices in King County, USA. The dataset used for this project contains information about various features of houses sold in the county, including the sale price. The goal is to build predictive models that can accurately estimate house prices based on these features.

## Getting Started

To run this project, you will need the following prerequisites:

- Python (version 3.7 or higher)
- Jupyter Notebook or any other Python environment that supports Jupyter Notebooks
- Required Python libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

You can install the necessary libraries using the following command:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Project Structure

The project is organized into several sections within a Jupyter Notebook:

1. **Data Wrangling**: In this section, the provided dataset (`kc_house_data.csv`) is loaded and preprocessed using the `wrangle` function. This function handles data cleaning, transformation, and filtering to prepare the data for analysis.

2. **Data Exploration and Visualization**: This section provides a comprehensive overview of the dataset. It includes information about the dataset's size, data types, missing values, and statistical summaries. Visualizations such as heatmaps, histograms, and scatter plots are used to explore relationships between different features and the target variable (price).

3. **Data Modeling**: In this section, predictive models are built and evaluated. Three different regression models are explored:

   - Linear Regression
   - Random Forest Regression
   - Decision Tree Regression
   
   Each model is trained on the dataset, and evaluation metrics such as Root Mean Squared Error (RMSE) and R-squared (R2) are calculated to assess their performance.

4. **Using Pipelines**: This section demonstrates the use of scikit-learn pipelines to streamline the preprocessing and modeling steps. A Random Forest model is built using a pipeline, and hyperparameter tuning is performed using GridSearchCV.

5. **Making Predictions**: A function named `make_prediction` is defined to make predictions on new data. This function takes various house features as input and returns an estimated house price using the trained model.

## Running the Code

1. Download the dataset `kc_house_data.csv` and save it in the same directory as the Jupyter Notebook.
2. Open the Jupyter Notebook and run each cell sequentially to execute the code. Make sure to have the required libraries installed.

## Conclusion

This project provides insights into predicting house sale prices in King County, USA. By exploring the dataset, building and evaluating regression models, and using pipelines for efficient modeling, it demonstrates the process of analyzing and predicting real estate prices based on various features. The provided `make_prediction` function allows for making price predictions on new data using the best-performing model.