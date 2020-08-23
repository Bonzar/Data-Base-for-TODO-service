# Data-Base-for-TODO-service
Data storage model for the Task manager service (todo list, diary, calendar).

This project I did as a course in the course of training, and for familiarization with it, I present you two variations of it:
1. Full database with test data from the filldb service
2. A clean database skeleton, the creation process of which is described in the attached files.

P.S: In both cases, there are foreign keys, triggers, functions, etc.

### Clean database
To recreate the database structure, you need to:
  - Run the script "PLAYME" in your MySQL client located in the "Clean" directory.
  
      `SOURCE PLAYME.sql`

*You can observe the process of creating tables, adding foreign keys, creating triggers, procedures, functions, and views in the corresponding files.*
      
### Filled darabase
To recreate a full database, upload its dump (from the "full_DB" directory) in your MySQL client:
  1. Create database 'Data-Base-for-TODO-service' in your MySQL client:
  
      `CREATE DATABASE 'Data-Base-for-TODO-service'`
  2. Load the database dump from cmd/bash:
  
      `$ mysql Data-Base-for-TODO-service < full_database.sql`
      
*Examples of selections for a populated database are provided in the "SELECT.sql" file, including using JOIN and window functions.*

## ER Diagramm of database
![Картинка](https://github.com/Bonzar/Data-Base-for-TODO-service/blob/master/ERDiagram.png)
