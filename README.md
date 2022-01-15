**Bivaraite Analysis:**



# Shopping-Mall-Customer-Segmentation
![KMeans_Bivariate_Clustering](https://user-images.githubusercontent.com/64422300/149489486-f3080e02-7ff7-4a15-855d-93f979e36ed5.png)

Code implemantion for connecting Python databse to MYSQL databse:
  
   ***!pip install pymysql***
    
    # import the module
     import pymysql
     import mysql.connector as connection
     #from mysql.connector import Error
     import pandas as pandas
     from sqlalchemy import create_engine
     # create sqlalchemy engine
     engine = create_engine("mysql+pymysql://{user}:{pw}@localhost/{db}" .format(user="root", pw="0003", db="Mall_CustomerSegmentation"))
                      
    # Insert whole DataFrame into MySQL
    df.to_sql('Mall_CustomerSegmentation', con = engine, if_exists = 'append', chunksize = 1000,index=False)
  
     #Insert whole dataframe to MYSQL
     df.to_sql('Mall_CustomerSegmentation', con = engine, if_exists = 'append', chunksize = 1000, index = False)
