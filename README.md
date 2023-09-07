# CSV data to PostgresSQL
#### [Employee Dataset from Kaggle.com](https://www.kaggle.com/datasets/ravindrasinghrana/employeedataset)
<hr>
  
In this project, I use a Kaggle dataset based on Employees in a fictional company. 

For the data process, I did ETL using Python with Pandas and Psycopg2 to create the employee database on PostgresSQL.

If you want to run this project on your PC, You'll need to install:

  - PostgresSQL 
  - Jupyter
  - Pandas and Psycopg2

Pay attention in create_database function, and set your PostgreSQL credentials correctly.

Now you can run the Nootebok and check your employees database in PostgreSQL.

[Click here to see the Notebook](https://github.com/MatheusSanteago/Data-Model/blob/master/etl/main.ipynb)

### Data model 

![Data Model](https://github.com/MatheusSanteago/Data-Model/blob/master/img/Employees.png)

### Data flow 

![Data Flow](https://github.com/MatheusSanteago/Data-Model/blob/master/img/datasource.png)
