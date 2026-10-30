# IBM Applied Data Science Capstone: SpaceX Falcon 9 First Stage Landing Prediction
This project aims to predict whether the first stage of the SpaceX Falcon 9 rocket will land successfully
using historical launch data. Predicting this outcome allows for accurate launch cost estimation, which 
is a key competitive advantage in the commercial space industry.

# Methodology
* Data Collection: I used the SpaceX REST API and web scraping(using BeautifulSoup) from Wikipedia to gather
  launch data.
  
* Data Wrangling: I handled missing values and encoded categorical variables.
  
* Exploratory Data Analysis (EDA): I used SQL queries for data extraction and Pandas and Seaborn for data visualization.

* Interactive Visual Analytics: I used interactive maps buitls with Folium to analyze launch sites
  and an interactive web dashboard created with Plotly Dash.

* Predictive Modeling (Machine Learning): I evaluate different models like Logistic Regression, Support Vector Machines,
 Decision Trees, K-Nearest Neighbors) and GridSearchCV for hyperparameter tuning.

# Technologies and Libraries
* Languages: Python, SQL
* Libraries: Pandas, NumPy, Matplotlib, Seaborn, Folium, Dash, Scikit-Learn, BeautifulSoup

# Results and Conclusion
 The best performance was using Tree Classificator with an accuracy of 0.8625 and a score of 0.888.

# Repository Structure


