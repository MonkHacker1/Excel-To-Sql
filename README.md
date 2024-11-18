# **ExcelToSQL 📊 ➡️ 🗄️**

This Python script is a simple and effective tool that allows you to convert Excel files into a SQL database. Perfect for those looking for a quick and easy solution to migrate data from spreadsheets to a SQL database.
## **🚀 Getting started**

First, clone this repository on your local machine using **`https://github.com/JCastro-bit/EXCEL-TO-SQL.git`**.

 Make sure you have Python , pymysql, openpyxl, sqlalchemy and Pandas installed in your environment.

## **🛠️ Installation**

1. Clone the repository
    
    ````python
    git clone https://github.com/JCastro-bit/EXCEL-TO-SQL.git
    ```
    
2. Change to the project directory
    
    ````python
    cd exceltosql
    ```
    
3. Install the required packages
    
    ````python
    pip install pymysql
    pip install openpyxl
    pip install sqlalchemy 
    pip install Pandas 
    ```
    

## **⚙️ Usage**

1. Place your **`.xlsx`** file in the project folder.

2. Add the database credentials.
    
    ````python
    # Create the database connection
    engine = create_engine('mysql+pymysql://root:0000@localhost:3306/database')
    ```
    
3. In the **`exceltosql.py`** script, update the filename in the line that says **`df = pd.read_excel('filename_of_your_file.xlsx')`**.

4. Run the script using Python.
    
    ````python
    python exceltosql.py
    ```

And that's it, your Excel data is now in your SQL database!
