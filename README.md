## DATA MIGRATION CAPSTONE PROJECT 2

## Project Overview
The objective of this project is to construct an Extract Load (EL) pipeline in Python to efficiently transfer the World Port Index data from the Access database to the PostgreSQL database.

## Project Instructions:

1. ** Build an Extract Load (EL) pipeline using Python to move the World Port Index data from the Access database to PostgreSQL.

2. **Solve SQL Queries**: Address the following SQL queries using the migrated data:
    1. What are the 5 nearest ports to Singapore's JURONG ISLAND port?
    2. Which country has the largest number of ports with a cargo_wharf?
    3. Which port has the nearest access to provisions, water, fuel-oil, and diesel?

## How It Works
1. **Data Extraction**: Begin by connecting to the Access database. Install and import the necessary Python libraries: `pyodbc` and `pandas`.

2. **Connecting to Access Database**: Create a function named `connect_to_database`, which takes the `database_path` as an argument. This path points to the Microsoft Access database file. The function constructs a connection string using the provided path and the Microsoft Access ODBC driver. Use the `pyodbc.connect()` function to establish the database connection and return the connection object.

3. **Retrieving the Table Names**: Develop a function that takes a valid database connection object as an argument. This function retrieves the names of tables from the database using a list comprehension and the `tables()` method of the cursor. It filters for tables by specifying `tableType="TABLE"`.

4. **Loading the Table**: Install and import the necessary Python libraries such as `psycopg2` and `sqlalchemy`. Create a connection to the PostgreSQL database engine.

## Loading the Data
The process of loading the data involves transferring the World Port Index dataset from the Access database to the PostgreSQL database. This is achieved through a well-defined Extract Load (EL) pipeline developed using Python and the mentioned libraries.

## Requirements for successful project execution:
- Python 3.x
- `pyodbc` library
- `pandas` library
- `SQLAlchemy` library
- PostgreSQL database

## Conclusion
 This project involved the retrieval of the World Port Index dataset from the Access database. This was achieved by connecting to the Access database using the `pyodbc` and `pandas` libraries. The dataset was then migrated to the PostgreSQL database using the `psycopg2` and `SQLAlchemy` libraries.

## Contribution/Feedback
Contributions and feedbacks encouraged. 
