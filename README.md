# Restaurant-Consumer-Analysis

## Nature of the Dataset

The dataset used in this project is a consumer dataset related to restaurant-goers. It contains various attributes about consumers, including demographic information, lifestyle choices, and geographical details. The dataset appears to have been collected to understand consumer behavior and preferences in the context of dining out.

### Dataset Attributes

The dataset includes the following columns:
- **Consumer_ID**: A unique identifier for each consumer.
- **City**: The city where the consumer resides.
- **State**: The state where the consumer resides.
- **Country**: The country where the consumer resides.
- **Latitude**: The latitude coordinate of the consumer's location.
- **Longitude**: The longitude coordinate of the consumer's location.
- **Smoker**: Indicates whether the consumer smokes (Yes/No).
- **Drink_Level**: The consumer's drinking level (e.g., Abstemious, Social Drinker, Casual Drinker).
- **Transportation_Method**: The primary mode of transportation used by the consumer (e.g., On Foot, Public, Car).
- **Marital_Status**: The marital status of the consumer (e.g., Single, Married).
- **Children**: Indicates whether the consumer has children (e.g., Independent, Kids).
- **Age**: The age of the consumer.
- **Occupation**: The occupation of the consumer (e.g., Student, Employed).
- **Budget**: The budget level of the consumer for dining out (e.g., Low, Medium, High).

The dataset consists of 138 rows and 14 columns, representing 138 unique consumers.

## Project Overview

### Data Loading and Preparation

The project involved loading the dataset into a pandas DataFrame for ease of manipulation and analysis. The initial steps included importing necessary libraries such as `numpy`, `pandas`, `matplotlib.pyplot`, `seaborn`, `plotly.graph_objects`, and `plotly.express`. Additionally, warnings were suppressed to maintain a clean output.

### Data Exploration

The dataset was explored to understand the distribution of different attributes and identify any patterns or anomalies. This involved:
- Viewing the first few rows of the dataset to get an overview.
- Checking for missing values and handling them appropriately.
- Summarizing the data to understand the general statistics of each column.

### Data Visualization

To gain deeper insights, various visualizations were created using libraries such as `matplotlib`, `seaborn`, and `plotly`. These visualizations helped in:
- Understanding the geographical distribution of consumers.
- Analyzing the relationships between different attributes like age, budget, and occupation.
- Identifying trends and patterns in consumer behavior, such as the correlation between drinking levels and transportation methods.

## Relevance to Data Science

This project is highly relevant to data science for several reasons:

1. **Data Wrangling**: The process of loading, cleaning, and preparing the dataset is a fundamental skill in data science. Handling real-world data often requires dealing with missing values, inconsistencies, and various data types.

2. **Exploratory Data Analysis (EDA)**: EDA is crucial for understanding the underlying structure and patterns in the data. This project showcases how to perform EDA using both descriptive statistics and visualizations.

3. **Visualization Skills**: Creating effective visualizations is essential for communicating insights. This project utilized various visualization tools to present the data in an understandable and insightful manner.

4. **Consumer Behavior Analysis**: Understanding consumer behavior is a common application of data science in industries such as marketing, retail, and hospitality. This project demonstrates how to analyze such data to gain insights that can inform business strategies.

5. **Geospatial Analysis**: The inclusion of geographical coordinates (latitude and longitude) allows for geospatial analysis, which is a valuable skill in fields like urban planning, logistics, and location-based services.

Overall, this project highlights the practical application of data science techniques to analyze and derive insights from consumer data, making it a valuable example of how data science can be used to inform and improve business decisions.
