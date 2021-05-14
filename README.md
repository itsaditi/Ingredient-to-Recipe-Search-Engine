# Ingredient-to-Recipe-Search-Engine

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
Inside virtualenv:

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
