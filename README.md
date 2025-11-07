# Capstone Project for IBM Data Science Professional Certificate

This project analyzes SpaceX mission data—collected via the SpaceX API and web-scraped mission records—to understand drivers of first-stage reusability.
Using Python (pandas, NumPy, seaborn, Folium, Dash), the exploratory analysis profiles launch sites, orbits, payload ranges, and landing outcomes to reveal patterns linked to successful recovery.
Finally, several machine-learning models are trained and evaluated to gauge their ability to predict landing success on future missions.

This project is intended to demonstrate an understanding of the data science workflow, tools, and techniques. Some, but not all, of the tools and techniques demonstrated are as follows.
### Core Languages & Environments
- **[Python](https://www.python.org/)** – Core programming language for analysis and modeling  
- **[Jupyter Notebook](https://jupyter.org/)** / **[JupyterLab](https://jupyter.org/try)** – Interactive coding and visualization environment  
- **[IBM Watson Studio](https://www.ibm.com/cloud/watson-studio)** – Cloud-based workspace for data science projects  
- **[GitHub](https://github.com/)** – Version control and project hosting  

### Data Collection & Processing
- **[Requests](https://requests.readthedocs.io/)** – Accessing APIs and web data  
- **[BeautifulSoup (bs4)](https://beautiful-soup-4.readthedocs.io/en/latest/)** – Web scraping from HTML pages  
- **[SpaceX REST API](https://github.com/r-spacex/SpaceX-API)** – Source of mission and launch data  
- **[SQLite](https://www.sqlite.org/)** / **[SQLAlchemy](https://www.sqlalchemy.org/)** / **[ipython-sql](https://pypi.org/project/ipython-sql/)** – Querying and managing structured data  
- **[NumPy](https://numpy.org/)** – Numerical computations and array manipulation  
- **[Pandas](https://pandas.pydata.org/)** – Data cleaning, wrangling, and exploration  

### Visualization & Dashboards
- **[Matplotlib](https://matplotlib.org/)** and **[Seaborn](https://seaborn.pydata.org/)** – Statistical and visual analysis  
- **[Folium](https://python-visualization.github.io/folium/)** – Interactive maps for launch sites  
- **[Plotly Dash](https://dash.plotly.com/)** – Building interactive web dashboards  

### Machine Learning & Model Evaluation
- **[Scikit-learn](https://scikit-learn.org/stable/)** – Training, evaluating, and tuning classification models  
- **Hyperparameter Tuning** – Grid search for optimal model performance  
- **Model Evaluation Metrics** – Accuracy, confusion matrix, precision, and recall  

---

## Techniques & Concepts

- **Data Collection:** Pulling structured data from APIs and unstructured data via web scraping  
- **Data Wrangling:** Cleaning, transforming, and normalizing mission and launch data  
- **Exploratory Data Analysis (EDA):** Understanding relationships between launch sites, payloads, orbits, and outcomes  
- **Feature Engineering:** Creating meaningful features to improve predictive models  
- **Visualization:** Using maps, scatterplots, and dashboards to interpret findings  
- **Machine Learning:** Training models (Decision Tree, KNN, SVM, Logistic Regression) to predict launch success  
- **Model Optimization:** Hyperparameter tuning and performance evaluation  
- **Dashboarding:** Building interactive analytical dashboards with Dash and Plotly  
