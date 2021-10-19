# sql-example1
sql example 1 - This is a basic example that shows how to use mysql.connector to connect to your database and create a table. In this example we create a table named "person" with two columns: Name and Last Name. The Name is chosen to be char (strange assumption just for this example) so a fixed-length string and Last Name is chose to be varchar so a variable-length string.
Here we can i create table into our program virtually with just connecting to DB:
          cursor.execute('DROP TABLE IF EXISTS demo;')
          print('Creating table sample')
          cursor.execute("CREATE TABLE data9 (Name varchar(230) NOT NULL, phoneNumber varchar(200) NOT NULL, City varchar(200))")
          
   This is the way you can create the Table on your program without using workbench.
