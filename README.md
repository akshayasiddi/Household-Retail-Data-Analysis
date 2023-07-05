# Retail Data Analysis and Interactive Web Application

This project is an interactive web application built using Flask to analyze retail data and provide insights into customer engagement and demographic factors. The application is hosted on Azure Cloud and utilizes various Azure services to store and process the data.

# Getting Started
To run the application locally, follow the steps below:

1. Clone the repository:
   
  ```   git clone https://github.com/akshayasiddi/Household-Retail-Data-Analysis.git ```

2. Install the required dependencies:
   
  ```   pip install -r requirements.txt ```

3. Set up Azure resources:

   Create an Azure SQL database to store the data.
   
   Update the database connection details in the config.py file.
   
4. Load the data:
  
  Place the sample and updated datasets (transactions, households, products) in the appropriate directories.
  
  Use the provided scripts or SQL queries to load the data into the Azure SQL database.

5. Run the application:

  ``` python app.py ```

6. Access the application:

Open a web browser and go to http://localhost:5000 to access the application.

# Features
- **User Authentication**: Users can create an account and log in to access the application.

- **Sample Data Display**: The application displays a sample data pull for a specific household number, showing relevant details from the household, transaction, and products tables.

- **Data Search**: Users can search and retrieve data based on a household number, sorted by various attributes such as basket number, date, product number, department, and commodity.

- **Demographic Factors Analysis**: The application provides a dashboard to analyze the impact of demographic factors on customer engagement, allowing users to explore factors like household size, presence of children, and income.

- **Data Update**: Users can load the most current datasets for transactions, households, and products to test the application's functionality and analyze the updated data.
