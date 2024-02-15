**Overview**
This work is designed to provide practical experience with Apache Spark DataFrames and the MLLib package for machine learning. Throughout this assignment, you'll learn how to set up a local Spark instance, manipulate and analyze data using Spark DataFrames, and apply machine learning techniques to real-world datasets. The tasks include data loading, cleaning, transformation, and the application of logistic regression to predict outcomes based on the data.

**Getting Started**
Prerequisites
Google Colab or a local Jupyter notebook environment
Basic understanding of Python programming
Familiarity with Apache Spark and machine learning concepts
Setup
Apache Spark Installation: The notebook begins with the installation of Apache Spark version 3.2.4 and setting up the necessary environment variables for Java and Spark.
PySpark and FindSpark Installation: Install pyspark version 2.4.0 and findspark, a utility that makes it easier to locate Spark on the system.
 Tasks
A. Spark Session Initialization
Initialize a Spark session to work with Spark DataFrames.
B. Data Loading and Preprocessing
Mount Google Drive: Connect Google Colab to Google Drive to access the dataset.
Load Dataset: Load the travel insurance dataset with schema inference and header recognition.
Data Inspection: Display the first 20 rows of the dataset to understand its structure.
C. Data Analysis
Rename Columns: For clarity, rename the "Commision (in value)" column to "Commission".
Data Analysis Tasks:
Compute and display the count of policies for each destination.
Analyze and print the mean age of customers by their claim status.
Identify the travel agency with the highest total commission.
D. Machine Learning Pipeline
Data Cleaning: Remove all rows with missing data.
Data Transformation:
Convert string columns to integers using StringIndexer.
Create dummy variables with OneHotEncoder.
Assemble a feature vector for model training.
Model Training and Evaluation:
Split the dataset into training and test sets.
Apply logistic regression to predict the probability of a customer making a claim.
Evaluate the model on both training and test datasets to compute accuracy.
Running the Code
Execute each cell in sequence, from installation and setup to data loading, preprocessing, analysis, and machine learning model application.
Ensure you have internet access when running the notebook in Google Colab for package installations and dataset access.
