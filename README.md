# ExploratoryDataAnalysis

This project showcases key methods in Exploratory Data Analysis (EDA), which is an essential initial step in any data science workflow. EDA helps to examine, visualize, and better understand the structure, features, and patterns in data. It provides critical insights that guide further analysis, feature engineering, and model selection, ensuring a data-driven approach to problem-solving.

## About the Libraries Used

This project primarily uses two powerful Python libraries:

+ `pandas`: Developed in 2008 by Wes McKinney, pandas was created to simplify data manipulation and analysis. It provides data structures and functions needed to work with structured data seamlessly. It allows easy handling of missing data, merging, reshaping, and performing statistical operations on data tables, making it a central tool in data science.

+ `matplotlib`: Created by John D. Hunter in 2003, matplotlib was designed to enable simple yet highly customizable data visualizations in Python. It provides a wide range of plotting functionalities, enabling analysts to visualize data patterns and insights through various chart types, such as line graphs, histograms, scatter plots, and more.

## Project Overview

This project consists of three notebooks, each focusing on different aspects of data analysis using Pandas:

+ `read_html.ipynb` deals with web-scraped data, where we load and clean a table of birth rates across regions of Ukraine from 1950 to 2019. The focus is on data cleaning, handling missing values, and basic visualization techniques.
+ `read_csv.ipynb` analyzes survey data from developers, where we clean the data, filter it for specific criteria, and compute salary statistics, demonstrating how to work with CSV files and perform data grouping and aggregation.
+ `kaggle_dataset.ipynb` explores a Kaggle dataset of Amazon's top-selling books over an 11-year period. It involves advanced data manipulation, such as renaming columns, aggregating data, and merging dataframes to analyze authors and their book ratings.

Together, these notebooks cover a wide range of Pandas functionalities, from basic data cleaning and exploration to more advanced aggregation and data manipulation techniques.

## Conda (Setup and Environment)

To make the project reproducible and ensure smooth package management, this project uses Conda as a package and environment manager. Below are the steps to set up the environment:


1. **Install Conda**:
If you haven't installed Conda yet, you can download it from the official [Anaconda](https://www.anaconda.com/products/individual) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) websites. Anaconda is a larger distribution with more pre-installed packages, while Miniconda is a smaller, minimal version. Choose whichever suits your needs.

2. **Create a new environment:** Open your terminal and run the following command to create a new Conda environment with Python 3.12:

    ```bash
    conda create --name new_conda_env python=3.12
    ```

3. **Activate the environment:** Once the environment is created, activate it by running:

    ```bash
    conda activate new_conda_env
    ```

4. **Install required packages (Jupyter, NumPy, MatPlotLib and Pandas)**

    ```bash
    conda install jupyter numpy matplotlib pandas
    ```

5. **Run Jupyter Notebook**

    ```bash
    jupyter notebook
    ```

***
## Conclusion

This project illustrates the overall importance of EDA in the data science process. It highlights how EDA helps in understanding the underlying structure of data and extracting meaningful insights. By leveraging tools like pandas and matplotlib, the project demonstrates foundational EDA techniques that can be applied to a wide range of data-driven challenges.