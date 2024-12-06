# WEB APPLICATION FOR VISUALIZING U.S. VEHICLE DATA

## PROJECT OVERVIEW

This project is based on creating and managing Python virtual environments, developing a web application, and deploying it to a publicly accessible cloud service RENDER.

The project used a dataset of car sales ads "vehicles_us.csv" although it was not primarily focused on the dataset or the analysis of it.

## STEPS:

### STEP 1: PROJECT REQUIREMENTS

- Create a GitHub account and start a new repository with the README.md and .gitignore files.
- Install the necessary packages, including pandas, streamlit, and plotly-express.
- Create a Render.com account and link it to the project repository on GitHub.
- Install and configure VS Code, setting the Python interpreter to match the virtual environment.

### STEP 2: DATA ACQUISITION

- Download the "vehicles_us.csv" database and place it in your project directory.

### STEP 3: DATA ANALYSIS AND VISUALIZATION

- Create a Jupyter Noteboo workbook called EDA.ipynb and perform an observation of the data
- Create histograms and scatter plots using plotly-express library.
- The plots made in Jupyter were the first prototype of the web project.

### STEP 4: WEB APPLICATION DEVELOPMENT

- Create the python file app.py in the project directory.
- Import the necessary libraries streamlit, pandas, and plotly_express.
- Load the data from the file "vehicles_us.csv" using Pandas and create the DataFrame "car_data".
- Incorporate Streamlit elements into the app such as Title, buttons, histograms, scatterplots and messages.
- Update the README file with the project description, instructions and each change that is made.

### STEP 5: DEPLOY IN RENDER

- Add the streamlit configuration file to the GitHub repository called "config.toml"
- Create a web service linked to the GitHub repository in Render.
- Configure the Render web service to install the necessary packages using the file "requirements.txt" and run the app.py file, all this with the command:
- BUILD COMMAND: pip install --upgrade pip && pip install -r requirements.txt
- START COMMAND: streamlit run app.py
- Deploy the final version of the application in Render.
- Verified the accessibility of the application at the link: https://tripleten-project-spring-6.onrender.com/

## CONCLUSION

This Streamlit application provides an interactive visualization of the "vehicle_us.csv" dataset. The application was developed as part of the Data Science assignment practice, namely the creation of Python virtual environments, the development of a web application and its deployment on a cloud service. The application is active and can be accessed. https://tripleten-project-spring-6.onrender.com/

PROJECT BY: GIORGIO RAMIREZ
