# StackOverflow Developer Survey - Data Analysis & Salary Prediction

## Project Motivation
This project is a part of the Udacity Data Scientist Nanodegree. My primary motivation for this analysis was to bridge the gap between two dynamic fields: data analytics and mobile software development. By diving into the StackOverflow Developer Survey data, I wanted to understand the compensation differences between data professionals and software developers, explore the work arrangement trends specifically within the mobile ecosystem (focusing on Dart/Flutter), and investigate whether having a coding side-hustle truly impacts a developer's job satisfaction. 

## Libraries Used
The analysis and machine learning models were built using Python. The following libraries are required to run the code:
* `pandas`: For data manipulation and analysis.
* `numpy`: For numerical operations.
* `matplotlib`: For creating static, animated, and interactive visualizations.
* `seaborn`: For drawing attractive and informative statistical graphics.
* `scikit-learn`: For building and evaluating the machine learning model (Linear Regression).

## Files in the Repository
* `survey_data_analysis.ipynb`: The main Jupyter Notebook containing the CRISP-DM steps (Business Understanding, Data Understanding, Data Preparation, Modeling, and Evaluation). All code, visualizations, and insights are documented here.
* `README.md`: This file, providing an overview of the project, its structure, and findings.
* *Note: The dataset itself is not included in this repository due to size constraints. You can download the full CSV file directly from the [StackOverflow Annual Developer Survey](https://survey.stackoverflow.co/) page.*

## Summary of Results
The analysis answered three main business questions and included a predictive model scenario:

1. **Salary Differences by Role:** Data Professionals generally report a higher average annual compensation compared to general Mobile/Software Developers, likely due to the highly specialized skill sets required for data-centric roles.
2. **Work Arrangements in the Mobile Ecosystem:** While remote and hybrid work dominate the tech industry, developers using Dart/Flutter showed a slightly higher inclination towards in-person work (~22%) compared to other technologies (~16%). Nevertheless, nearly 80% of mobile developers still enjoy flexible (remote/hybrid) setups.
3. **The Impact of Side Projects:** The data debunked the myth that developers must code in their free time to be happy. Job satisfaction rates were nearly identical for those who build side projects/hobbies (67.8%) and those who treat coding strictly as a 9-to-5 job (67.0%).
4. **Predictive Modeling:** A Multiple Linear Regression model was trained to predict salaries based on experience, education, and remote work status. For a hypothetical developer with a Bachelor's degree, working fully remotely, with 5 years of experience, the model predicted an annual salary of approximately $65,672. (Note: The R-squared score is ~0.05, which is expected given that massive salary drivers like geographic location and company size were intentionally excluded for this baseline scenario).

## Acknowledgements
* Data source: [StackOverflow Annual Developer Survey](https://survey.stackoverflow.co/)
* Project guidelines and framework: [Udacity Data Scientist Nanodegree](https://www.udacity.com/)
