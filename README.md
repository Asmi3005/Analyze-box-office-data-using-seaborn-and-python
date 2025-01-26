# Analyze-box-office-data-using-seaborn-and-python

## Overview  
This project focuses on analyzing and visualizing box office data using Seaborn and Python. By working with the TMDB dataset, we aim to understand trends, distributions, and relationships among various movie features and their impact on revenue.  

### Learning Objectives  
- Produce data visualizations with Seaborn.  
- Apply graphical techniques used in exploratory data analysis (EDA).  
- Generate publication-quality graphs to analyze data effectively.  

## Project Structure  

### Task 1: Data Loading and Exploration  
- Introduced to the project and its learning outcomes.  
- Familiarized with the Jupyter Notebook environment.  
- Imported essential libraries: `NumPy`, `pandas`, `matplotlib`, and `Seaborn`.  
- Loaded the TMDB dataset containing 7,400 movies and explored the first few entries.  

### Task 2: Visualizing the Target Distribution  
- Visualized the distribution of movie revenues using Seaborn's `distplot`.  
- Illustrated the skew in revenue by applying a logarithmic transformation with `np.log1p`.  

### Task 3: Comparing Film Revenue to Budget  
- Created subplots to visualize the distribution of budgets and the relationship between log-transformed budgets and revenues.  
- Performed log transformations for better interpretability of the data.  

### Task 4: Do Official Homepages Impact Revenue?  
- Created features to indicate the presence of an official homepage for each movie.  
- Used Seaborn's `catplot` to compare revenues of movies with and without official homepages.  

### Task 5: Distribution of Languages across Films  
- Analyzed the distribution of film languages using box plots.  
- Tested the hypothesis that English-language movies generate the highest revenue and analyzed deviations from this expectation.  

### Task 6: Common Words in Film Titles and Descriptions  
- Identified trends in movie titles and descriptions.  
- Created word clouds to visualize common words and their frequency.  
- Used these insights to understand the relationship between movie titles/descriptions and revenue.  

### Task 7: How do Film Descriptions Impact Revenue?  
- Tokenized and vectorized movie titles and descriptions.  
- Fitted a linear regression model to identify words with the highest impact on revenue.  
- Used `ELI5` to display high-impact words influencing revenue predictions.  

## Technologies Used  
- **Programming Language**: Python  
- **Libraries**: NumPy, pandas, matplotlib, Seaborn, WordCloud, scikit-learn, ELI5  

## Key Outcomes  
- Explored and visualized the TMDB dataset to understand trends in movie data.  
- Identified significant factors affecting box office revenue, such as budgets, homepages, languages, and descriptive words.  
- Developed skills in creating advanced visualizations and applying feature engineering techniques.  

## Dataset  
The TMDB dataset contains metadata for 7,400 movies, including features such as revenue, budget, language, and descriptions. The dataset can be accessed from the [Kaggle TMDB Box Office Prediction Competition](https://www.kaggle.com/c/tmdb-box-office-prediction).  


