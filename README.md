# DSX Local Credit Card Default Demo

**Objective**

The objective of this demo asset is to demonstrate how to use analytics to predict credit card default.  A client approves many low value merchant accounts without much scrutiny. Many of those merchant accounts default. 

This demo asset achieves these goals:
1. Understand profiles of merchants who have defaulted on their credit cards and share it with the acquisitions, marketing, and customer care teams
2. Create a predictive model for credit card default
3. Operationalize the model by deploying it for online scoring

**This repository contains the following assets for the Credit Card Default demo in DSX Local**
1. ![Presentation](Presentation)
2. ![Notebook](Notebooks)
3. ![Data](data)

**Demo setup**
1. Create a DSX project and name it "*DSX Local Lab - Credit Card Default*"
2. Import ![Data](data) <br/>
Tip: First download the csv files before importing them into your project.  When downloading the csv files, make sure click the **Raw** button to display the data in its raw format, right-click and select "Save Page As".
![Download CSV files](static/img/file_download.png?raw=true)
3. Import notebook <br/>
Within the "DSX Local Lab - Credit Card Default" project, add a Notebook and choose to import it from this URL: https://github.com/elenalowery/DSX-Local-Credit-Card-Default/blob/master/Notebooks/CreditCardDefault_DSXLocal.ipynb
4. Follow instructions in the notebook to add project token, and work through the notebook
5. If you would like to show Model Management - create several deployments from this or different notebooks

**Demo**
1. Follow the agenda in the presentation
2. During the demo show capabilities of DSX in the context of Credit Card Default use case
   * Start with the overview of the use case
   * Log in to DSX Local and create a new project
   * Show collaboration features for the project
   * Load data and explain what type of data sources are supported
   * Create a notebook from File
   * Walk through the notebook
   * Explain the deployment process - via UI and API
   * Test the model via UI or REST client and explain how Line of Business application will make the same call
3. Wrap up with architecture discussion 
