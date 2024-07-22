# IMDb Movie Data Analysis

This project involves the analysis of a dataset from IMDb, which includes various details about movies. The dataset is cleaned and analyzed using Python libraries such as pandas, matplotlib, seaborn and scipy.

## DAtaset

The dataset, `IMDbMovies.csv`, contains information about movies including their release year, director, main genres, budget, gross worldwide, and number of ratings.

## Data Cleaning

The data cleaning process involves:
- Loading the dataset into a pandas DataFrame.
- Removing duplicate rows and rows with missing values in certain columns.
- Filtering the data to include movies released after 2014.
- Renaming columns for better readibility.
- Changing data types of certain columns for appropriate analysis.
- Creating a new feature 'Revenue'.

## Data Analysis

The data analysis project includes:
- Finding the year with the highest average voting and highest average revenue.
- Calculating the average raring for each director.
- Checking the correlation between revenue and number of ratings using a heatmap.
- Comparing the revenues of action movies and drama movies using a t-test.

## Libraries Used

- pandas: For data manipulation and analysis.
- matplotlib: For creating static, animated, and interactive visualizations.
- seaborn: For statistical data visualization based on matplotlib.
- numpy: For numerical computations.
- scipy: For scientific computations including statistics.

##  Results

The results of the analysis are saved back into a cleaned CSV file, `cleaned_imdbmovies_data.csv`.

## Note

This is a summary of the project. For detailed analysis and code please refer to the Jupyter notebook.
