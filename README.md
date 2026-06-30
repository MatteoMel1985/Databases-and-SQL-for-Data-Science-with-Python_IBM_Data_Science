![Skills Network](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/assets/logos/SN_web_lightmode.png)

<h1 align="center">SQLite, SQL Magic, and Real-World Data Analysis with Python</h1>

This repository contains a set of Jupyter Notebook labs focused on accessing, creating, querying, and analysing SQLite databases with Python. The notebooks gradually move from basic database operations to more practical analytical workflows using real-world datasets, SQL queries, pandas DataFrames, and Python visualisation libraries.

The main purpose of this repository is to provide a structured reference for students learning how to combine SQL and Python inside JupyterLab. It covers essential database operations, SQL Magic commands, importing CSV data into SQLite, querying metadata, solving analytical problems, and visualising selected results.

<h1 align="center"><i>Notebooks Overview</i></h1>

* [**Create and Access SQLite Databases with Python**](./Week4_Insert_Update_SQLite.ipynb):

This notebook introduces the basic workflow for creating and managing a local SQLite database directly from Python. It demonstrates how to connect to a database with `sqlite3`, create a cursor object, define a table, insert records, run `SELECT` queries, fetch query results, update existing values, retrieve SQL results into a pandas DataFrame, and close the database connection correctly.

* [**Accessing Databases with SQL Magic**](./DB0201EN-Week3-1-3-SQLmagic_SQlite.ipynb):

This notebook explains how to use the `ipython-sql` extension to execute SQL commands directly inside JupyterLab cells. It shows how to connect to an SQLite database using `%sql`, create and populate a table with `%%sql`, pass Python variables into SQL queries, assign query results to Python variables, convert SQL results into pandas DataFrames, and visualise query outputs with Python plotting libraries.

* [**Analysing a Real-World Dataset with SQL and Python**](./DB0201EN-Week3-1-4-Analyzing_SQLite.ipynb):

This notebook applies SQL and Python to a real dataset containing selected socioeconomic indicators for Chicago community areas. It demonstrates how to download CSV data with pandas, store it as an SQLite table, inspect the dataset, and answer analytical questions using SQL. The exercises include counting rows, filtering community areas by hardship index, identifying the highest hardship index, retrieving high-income community areas, and visualising the relationship between per-capita income and hardship index with `seaborn`.

* [**Working with Real-World Data Using SQL and Python**](./DB0201EN-Week4-1-1-RealDataPractice-v5_sqlite_Learner.ipynb):

This notebook expands the real-world analysis workflow by using the Chicago Public Schools Progress Report Cards dataset. It shows how to load school performance data into SQLite, query database metadata with `sqlite_master` and `PRAGMA_TABLE_INFO`, and work with column names containing spaces, mixed case, and special characters. The lab also practises more advanced SQL operations, including sorting, limiting results, replacing characters in strings, casting values, grouping records, aggregating college enrolment by community area, and joining school data with census data to retrieve hardship index information.

<h1 align="center"><i>Skills Practised</i></h1>

* Creating and connecting to SQLite databases with Python.
* Creating tables and inserting records with SQL.
* Updating existing database records.
* Running SQL queries from both Python and Jupyter SQL Magic.
* Fetching SQL query results with `fetchall()` and `fetchmany()`.
* Loading CSV datasets into SQLite using pandas.
* Converting SQL query outputs into pandas DataFrames.
* Querying database metadata and table structures.
* Filtering, sorting, grouping, aggregating, and joining real-world data.
* Cleaning query outputs with SQL string functions such as `REPLACE()`.
* Casting string values into numerical values for analytical filtering.
* Visualising selected query results with `Matplotlib` and `seaborn`.

<h1 align="center"><i>Technologies Used</i></h1>

* Python
* SQLite
* `sqlite3`
* `ipython-sql`
* pandas
* Matplotlib
* seaborn
* JupyterLab

<h1 align="center"><i>Repository Structure</i></h1>

```text
.
├── Week4_Insert_Update_SQLite.ipynb
├── DB0201EN-Week3-1-3-SQLmagic_SQlite.ipynb
├── DB0201EN-Week3-1-4-Analyzing_SQLite.ipynb
├── DB0201EN-Week4-1-1-RealDataPractice-v5_sqlite_Learner.ipynb
└── README.md
```

<h1 align="center"><i>Overall Summary</i></h1>

Together, these notebooks provide a practical introduction to using SQL and Python for database access and exploratory data analysis. They begin with the fundamentals of creating and querying SQLite databases, then progress towards analysing real public datasets through SQL, pandas, and visualisation tools. The labs are especially useful for students who want to strengthen their understanding of relational databases while working inside a Python-based data analysis environment.

# Author

# ***[Matteo Meloni](https://www.linkedin.com/in/matteo-meloni-40a357154/)***
