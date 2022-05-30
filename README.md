# Car_model_recommendation
A predictive model built to recommend appropriate car model provided user's requirements. Presented through a basic CSS-styled web UI, also implemented using Python 3(Flask).

Libraries Used: numpy, pandas, flask, pickle, sklearn

Data Used: cars_engage_2022.csv acquired through Microsoft's Engages 2022 Internship Program.

Flow of functionality:
  1. Study the data and choose the features common to popular knowledge.
  2. Data Cleaning: filling missing/null values where possible, dropping row otherwise.
  3. Data Transformation: Merging attributes with high correlation and redundant data, trimming out unnecessary parts of the data and performing appropriate type casting.
  4. Pre-processing: LabelEncoding categorical data and standardizing numeric attributes.
  5. Regression: Fitting the data into Decision Tree classifier. Followed readjustment in parameters to maximize accuracy and prevent overfitting.
  6. Flask Web-app: Integrating model's prediction funtion into a basic web-UI using flask. 
