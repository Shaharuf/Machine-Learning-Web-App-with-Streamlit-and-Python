# Machine Learning Web App with Streamlit and Python
This is a simple web application built with Streamlit and Python to demonstrate how to deploy a machine learning model in a web app.

The app is built using the Iris dataset and a Random Forest classifier to predict the species of an iris flower based on its sepal length, sepal width, petal length, and petal width.

# Getting Started
To run this web app on your local machine, follow the instructions below.

# Prerequisites
You need to have Python 3.6 or later installed on your computer. You can download Python from the official website: https://www.python.org/downloads/

# Installing Dependencies
To install the required dependencies, run the following command:

bash
pip install -r requirements.txt


# Running the App
To run the app, navigate to the project directory and run the following command:

bash
streamlit run app.py
This will start the web app and open it in your default browser.

# About the App
The web app has a simple interface where you can input the values of the four features of an iris flower and get the predicted species as output.

The app also has a sidebar where you can select different parameters for the Random Forest classifier used in the model. You can change the number of trees, the maximum depth of the trees, and the criterion used to split the nodes.

The code for the machine learning model and the web app is provided in the model.py and app.py files, respectively. The data/ directory contains the Iris dataset used in the app.

# Acknowledgments
This project was inspired by the Streamlit tutorial on building a data app: https://docs.streamlit.io/en/stable/tutorial/create_a_data_explorer_app.html. The code for the Random Forest classifier was adapted from the scikit-learn documentation: https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html.
