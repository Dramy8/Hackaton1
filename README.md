# AI Powered Personalized Content Recommendation System

## Project Overview

This project was developed as part of a Data Analytics Hackathon.

The goal was to build a simple personalized recommendation system using Python and data analysis.  
Instead of using a complex machine learning model, this project uses a clear rule-based approach: the system compares a user profile with different recommendation options and selects the best match.

The project was designed to stay understandable, realistic, and easy to explain.

## Dataset

The project uses a synthetic dataset created for learning purposes.  
It contains user profiles, content preferences, activity types, engagement scores, content popularity, and recommendation-related information.

Because the dataset is synthetic, the results should be interpreted as a simulation rather than real user behavior.

## Technologies Used

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

- `Personalized Content Recommendation System.ipynb`  
  Main notebook containing the full analysis, statistical tests, visualizations, and recommendation system.

- `users_generated_dataset_enriched.csv`  
  Synthetic dataset used for the project.

## Key Steps

1. Load and inspect the dataset
2. Clean missing values and inconsistent categories
3. Explore user interests, activity types, engagement, age, and content behavior
4. Use NumPy and Pandas for numerical analysis
5. Apply SciPy statistical tests:
   - Chi-square test
   - Pearson correlation
6. Build a recommendation options DataFrame
7. Create a simple scoring system based on:
   - interest match
   - preferred format match
   - content popularity
8. Compare recommendation options and select the highest scoring content
9. Apply the recommendation engine to the dataset
10. Visualize insights and recommendation results

## Main Insight

This project helped me understand how data analysis can be connected to a practical recommendation system.  
Even with simple rules, user preferences can be transformed into personalized suggestions that could be used in platforms such as learning websites, music apps, fitness apps, or content platforms.

One limitation is that the dataset is synthetic. It was useful for building and understanding the project, but real user data would probably lead to deeper and more surprising insights.

## Author

Auriane Bouaziz
