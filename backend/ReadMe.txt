[X] Installing virtualenv
pip3 install virtualenv

[X] To check whether virtualenv exists and its version
virtualenv --version

[X] Creating virtual environment in directory
cd flaskproj
virtualenv env
# virtualenv env: Creates env folder

[X] Start Windows Subsystem for Linux (WSL) by typing-
WSL

[X] Activate the virtualenv
source env/Scripts/activate

Inside virtualenv:

[X] Install flask_MYsql-
pip3 install pymysql

[X] To run the code: python3 main.py

This code reads the parsed JSON and creates the database and the following tables:
receipe_title
receipe_instru
receipe_ingre