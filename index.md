# Ingredient-to-Recipe-Search-Engine

Identified system requirements and designed a relational database schema that met the constraints and gave the list of recipes for the given input list of ingredients. 45000 recipes were scrapped from foodnetwork.com using Python to populate the database. MySQL was used to query the designed database. An Interface was created using Flask (Python Web Framework).

[Video Demo](https://youtu.be/b1KRo5usTh4)

[DB Schema](https://github.com/itsaditi/Ingredient-to-Recipe-Search-Engine/blob/main/DB_Schema.jpeg)
### Installing virtualenv
```bash
pip3 install virtualenv
```

### To check whether virtualenv exists and its version
```bash
virtualenv --version
```

### Creating virtual environment in directory
```bash
cd flaskproj
virtualenv env
```

#### virtualenv env: Creates env folder

### Start Windows Subsystem for Linux (WSL) by typing:
```bash
WSL
```

### Activate the virtualenv:
```bash
source env/Scripts/activate
```
## Inside virtualenv:

### Install flask_MYsql:
```bash
pip3 install pymysql
```

### To run the code: 
```bash
python3 main.py
```

This code reads the parsed JSON and creates the database and the following tables:
* receipe_title
* receipe_instru
* receipe_ingre
