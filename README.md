# COVID-19 Data Analysis and Visualization

## Project Description

This project involves loading, cleaning, exploring, and visualizing COVID-19 data for selected countries (Kenya, USA, and India). The analysis uses the `pandas` library for data manipulation and `matplotlib` and `seaborn` for plotting. The goal is to provide insights into the trends of COVID-19 cases, deaths, and vaccinations over time.

## Objectives

* Load COVID-19 data from the "owid-covid-data.csv" file.
* Clean the data by handling missing values and filtering for specific countries.
* Perform exploratory data analysis (EDA) to understand the data.
* Visualize total cases, total deaths, daily new cases, and death rates over time.
* Visualize vaccination progress by plotting cumulative vaccinations over time.

## Tools and Libraries Used

* `pandas`: For data manipulation and analysis.
* `matplotlib.pyplot`: For creating basic plots.
* `seaborn`: For enhanced and more visually appealing plots.

## How to Run/View the Project

1.  **Prerequisites:**
    * Python 3.x
    * `pandas`
    * `matplotlib`
    * `seaborn`

2.  **Installation:**
    * Clone the repository: `git clone <https://github.com/mwikali29/week8-python.git>`
    * then open with anaconda
    * Install the required packages: `pip install pandas matplotlib seaborn`

3.  **Running the Code:**
    * Ensure that the "owid-covid-data.csv" file is in the same directory as the Python script.
    * Run the Python script: `python week 8 project.ipynb`  

4.  **Viewing the Results:**
    * The script will display the first few rows of the dataset, information about the dataset structure, and missing values before and after cleaning.
    * The script will generate several plots:
        * Total Cases Over Time
        * Total Deaths Over Time
        * Daily New Cases
        * Death Rate (Total Deaths / Total Cases) Over Time
        * Cumulative Vaccinations Over Time
    * The plots will be displayed on the screen.  Ensure you have a graphical environment set up to view the plots.


INSIGHTS AND REFLECTIONS
* USA has the highest total cases and deaths by a significant margin.
* Countries with high population density have most death rates and daily cases compared to lowly populated countries
* Death rates vary significantly between countries, potentially reflecting differences in healthcare system and infrastructure,
* and many more that are stated in the file.

The project demonstrates how data analysis and visualization can be used to understand the spread of COVID-19 and the progress of vaccination efforts.  Further analysis could explore the impact of interventions, regional differences, and other factors.



