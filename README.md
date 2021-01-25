# SQL Analytics problem

This problem requires data preprocessing, data visualization, and model training. You should provide sufficient evidence that your solution is complete by, as a minimum, indicating that it works correctly against the supplied data.

## PROBLEM: Query Analytics

You’re a Senior Data Scientist at an insurance company that focuses on cars and motorcycles. The company wants to optimize the performance of its database. To understand how the database processes the query you can use any query processing and analyzing techniques. The data needed for the activity is in the data folder that contains:

- ```general_log.json```: is the record of what the database is doing. The server writes information to this log when clients connect or disconnect, and it logs each SQL statement received from clients.
- ```slow_log.json```: is a record of SQL queries that took a long time to perform.
- ```tpch.sql```: the DDL of the database for query generation. Queries are generated from the TPC-H Benchmark: http://www.tpc.org/tpch/.

The activity consists of three tasks, you must complete at least one.

### Data Visualization

Use a visualization library to visualize your data in a number of ways, including line and bar charts, scatterplots, and histograms. You can leverage the library directly in your Python scripts, Jupyter notebooks, iPython shells, and other platforms. Starting from the provided data extract information such as: tables and fields used in queries, frequent operations etc.. Extract statistics on your data to better understand what you’re working with.

### Model Training

Use the query text to train a model that can predict the query execution time. Choose the right algorithm for your business problem to building accurate models. Your task is to provide the best model you can with the provided data. For the current scenario, consider the following questions:

1.	Is machine learning appropriate for this problem, and why or why not?
2.	What is the ML problem if there is one, and what would a success metric look like?
3.	What kind of ML problem is this?
4.	Is the data appropriate?

### Model Deploy

Your task is to apply DevOps principles to ML. The model folder contains an example model you can use to:
- Automate the creation of the infrastructure and the setup of the application. 
- Recover from crashes. Implement a method autorestart the service on crash. 
- Notify any CPU peak Implements a CI/CD pipeline for the code.
- Scale when the number of request are greater than 10 req /sec.

For this task you can also use your own model. The main purpose is to define model deployment of an ML-model as the process of integrating the model into a production environment. There is an example ```main.py``` and a ```Dockerfile```, feel free to change them.

## General requirements
- You may use whatever programming language/platform you prefer. Use something that you know well.
- You must release your work with an OSI-approved open source license of your choice.
- You must deliver the sources of your application, with a README that explains how to compile and run it.
- Add the code to your own Github account and send us the link.

**IMPORTANT:**  Implement the requirements focusing on **writing the best code** you can produce.

