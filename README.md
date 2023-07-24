## Creating sqlite3 data base in python environment 


## General Information
Sometimes it is more efficient to query a very big database using sql then using python to further manipulate/ analyse it. In the code, I tried to do imitate the same in a smaller scenario.

I have used the yahoo finance data for reference.

## Technologies Used
* Python and SQL: The programming language used for this project.
* Libraries:
    * requests: Used to send HTTP requests and retrieve data from Yahoo Finance.
    * pandas: Utilized to manipulate and structure the data into a DataFrame.
    * StringIO: Used for efficient string operations during data processing.
    * sqlite3: SQLite is a C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine


## Usage
To use this tool effectively, follow these steps:

* Clone the repository to your local machine.
* Install the required libraries using pip install requests pandas.
* Follow the instructions inside the code for sqlite3.

## Room for Improvement:
As it was my first ever using sqlite3 in python environment. There are several areas that can be further looked into:

* Data Validation: Validate input parameters to ensure they are appropriate and correctly formatted.

* Data Preprocessing: Include data preprocessing steps to handle missing values, outliers, or formatting inconsistencies.

* Improve efficacy: There might be other libraries to streamline the process such as using SQLAlchemy.
