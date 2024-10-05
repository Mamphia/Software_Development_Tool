# Streamlit Web Application for Vehicle Data Visualization

## Project Overview

This project revolves around the application of key software engineering tasks, aiming to supplement your data skills and increase your marketability for potential employers. The primary tasks involve creating and managing Python virtual environments, developing a web application, and deploying it to a publically accessible cloud service.

The project utilized a dataset of car sales advertisements, although the focus was not primarily on the dataset or the analysis. You're free to choose any dataset that interests you.

## Steps Involved

### Step 1: Project Prerequisites

- Created a GitHub account and initialized a new repository with README.md and .gitignore files.
- Installed necessary packages including pandas, streamlit, and plotly-express.
- Created a Render.com account and linked it to GitHub.
- Installed and configured VS Code, setting the Python interpreter to match the virtual environment.

### Step 2: Data Acquisition

- Downloaded the car advertisement dataset (vehicles_us.csv) and placed it in the root directory of the project.

### Step 3: Exploratory Data Analysis

- Created an EDA.ipynb Jupyter notebook to conduct exploratory data analysis.
- Created histograms and scatterplots using the plotly-express library.
- The visualizations were first prototyped in Jupyter notebook and then integrated into the web application.

### Step 4: Web Application Development

- Created an app.py file in the root directory of the project.
- Imported necessary modules like streamlit, pandas, and plotly_express.
- Loaded the CSV data into a pandas DataFrame.
- Incorporated various streamlit components into the app like headers, histograms, scatter plots, and checkboxes.
- Updated README file to include a basic project description and instructions for other users to run the project on their local machine.

### Step 5: Deployment to Render

- Added a streamlit configuration file to the GitHub repository.
- Created a new web service linked to the GitHub repository in Render.
- Configured the Render web service to install necessary packages and run the app.py file.
- Deployed the final version of the application on Render.
- Verified the application's accessibility at: https://software-development-tool.onrender.com

### How To Run This Project Locally
If you're interested in running this project locally on your own machine, please follow along with the steps provided below -

- Clone this repository and store it locally
- As you add new Streamlit components to develop your application, you can run the streamlit run app.py command from the terminal to see what the result will look like. Do this on your local machine (preferably from a system terminal) to test that everything works before committing and pushing your changes to your own GitHub repo, if you choose to.
- After running streamlit run app.py, you should be able to access your local test deployment using the port http://0.0.0.0:10000
If successful, if should see your streamlit displaying your app. However, if unsuccessful, you'll see a message that states a potential cause for an unsuccessful build. Fix the error, save, and run the command again.

## Conclusion

This Streamlit application provides an interactive visualization of the Vehicle dataset. The app was developed as part of practicing software engineering tasks, namely creating Python virtual environments, developing a web application, and deploying it on a cloud service.
