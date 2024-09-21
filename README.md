# yelp-data-set-analysis-
Yelp Dataset Analysis Project
Overview
This project focuses on analyzing three key datasets from Yelp: business, review, and user data. The goal is to explore various questions related to Yelp's food establishments and their reviews, such as the relationship between ratings and review count, the effect of happy hour, and the identification of top-performing establishments. Additionally, it explores linguistic cues in reviews, such as the use of exclamation points, and their relationship to ratings.

Project Structure
Data Loading and Exploration

Three datasets are loaded:
yelp_academic_dataset_business.csv
yelp_academic_dataset_review.csv
yelp_academic_dataset_user.csv
Each dataset's structure is explored using .head() and .info() methods to understand the data fields and types.
Missing values are visualized using the missingno library to identify gaps in the data.
Data Cleaning

Numerical and categorical columns are identified for the business dataset.
Missing values in numerical columns are filled with the mean, while those in categorical columns are filled with the mode.
Any remaining missing values are checked to ensure data integrity.
Analysis and Visualization
Several analyses were conducted using visualizations and statistical techniques:

Q1: Do businesses with more reviews tend to have higher ratings?
Visualization and correlation analysis showed that reviews and ratings are not strongly correlated.
Q2: Is there a difference in the rating distribution of food establishments by state?
Box plots and distribution plots revealed no significant difference in ratings across states.
Q3: Investigate differences in food establishments with/without a Happy Hour.
Establishments offering happy hour generally have more reviews, as seen in bar plot comparisons.
Advanced Analyses

Q4: Yelp’s Best Local Food Establishment Award
A custom Python script was created to find food establishments with the highest star ratings and review counts in each city. These establishments are awarded the "Best Local Food Establishment" title.
Q5: Relationship Between Exclamation Points and Ratings
An analysis of the use of exclamation points in reviews showed a correlation with either very high or very low ratings, suggesting that exclamations are often tied to strong emotions.
Installation
To run this project locally, you'll need to install the required dependencies:

bash
Copy code
pip install pandas matplotlib seaborn missingno yfinance fredapi
You can install additional dependencies mentioned in the notebook via the following command:

bash
Copy code
pip install -r requirements.txt
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/yelp-dataset-analysis.git
cd yelp-dataset-analysis
Run the Jupyter Notebook to explore the analyses and visualizations.

Follow the steps provided in the notebook to reproduce the results and explore additional insights.

Data Sources
Yelp Business Data: Contains business information such as name, category, and location.
Yelp Review Data: Includes user-generated reviews and star ratings.
Yelp User Data: Contains data on individual users, including their review history.
Key Findings
There is no strong relationship between the number of reviews and ratings.
Ratings are consistent across states, with no clear difference between them.
Establishments offering happy hours tend to receive more reviews.
Highly rated food establishments with the most reviews in each city are recognized as "Best Local Food Establishments."
Reviews with exclamation points often reflect extreme opinions, either very positive or very negative.
Conclusion
This project showcases various data analysis techniques and insights from Yelp's business, review, and user data. From analyzing business performance to linguistic patterns in reviews, this analysis can provide valuable information for businesses and platforms like Yelp.

License
This project is licensed under the MIT License.

Feel free to adjust any specific parts or add more details as needed! Let me know if you need further tweaks.






