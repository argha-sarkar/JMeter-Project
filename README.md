  
# JDBC Connection Configuration

A brief description of what this project does and who it's for


## Acknowledgements
Right now I'm uploading Python Basics Cheat sheet, I will upload the numpy,
pandas, matplotlib, seaborn in the future.

 - [JDBC Connection Configuration](https://github.com/argha-sarkar/JMeter-Project/tree/main/JDBC%20Connection%20Configuration)
 
## Authors

- [@argha-sarkar](https://github.com/argha-sarkar)

  
## Installation

- Install JAVA 8.0 above on windows
- After java installation and set u p complete then download and extract Apache JMeter
- Also install MySQL

    
## Environment Variables

To run all this project, you will need to the following environment 

`Windows`
  
## Description

After installation and enviroment setup done, first create a dtabase on MySql databases. The try to create a SQL table on the databases. Example -

- Create databases on MySQl-
```bash
CREATE DATABASE DB;
```

- Use Databases on MySQl-
```bash
USE DB;
```

- Create table-

```bash
CREATE TABLE table_name (
    tutorial datatype,
    author datatype,
    submission_date datatype,
);
```

- Insert into table - 
```bash
INSERT INTO tutorials_tbl 
    (title, author, submission_date)
    VALUES
    ("Learn PHP", "John Poul", NOW());
```

After database and table create compoleted, then open Apache Jmeter.
- Add directory class path or jar file on Apache JMeter
- Create JMeter Test Plan
- Create a Thread group in Test Plan
- Now adding to JDBC Requests inside the Thread Group
- Then create JDBC Request [Write SQL Query]
- Create Listener [View Results Tree]

## [Results]([https://raw.githubusercontent.com/argha-sarkar/Cheatsheet/main/image/Screenshot%20from%202021-08-20%2019-36-10.png](https://github.com/argha-sarkar/JMeter-Project/blob/main/JDBC%20Connection%20Configuration/img/Result.png))
  
## License

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)]((https://choosealicense.com/licenses/mit/))


MIT License

Copyright (c) [2021] [Argha Sarkar]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
  
