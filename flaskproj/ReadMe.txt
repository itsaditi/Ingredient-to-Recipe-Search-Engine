[X] Installing virtualenv
pip3 install virtualenv

[X] To check whether virtualenv exists and its version
virtualenv --version

[X] Creating virtual environment in directory
cd flaskproj
virtualenv env
# virtualenv env: Creates env folder

[X] Start WSL by typing-
WSL

[X] Activate the virtualenv
source env/Scripts/activate

Inside virtualenv:

[x]install flask and flask-sqlalchemy
pip3 install flask flask-sqlalchemy

[x] Create app.py in flaskproj

[X] To run app.py
python3 app.py

[X] Create static (for css and javascript) and templates folder inside flaskproj. 
No other names.
[X] Create index.html in templates


[X] TEMPLATE INHERITANCE: Creating one master HTML file that contains skeleton
of what each page is going to look like and you inherit that in each other page 
and insert code where you need it.

[X] Create base.html in templates folder. This will be our skeleton. 
Create bolierplate code in base.html.

[X] Boilerplate code or just boilerplate are sections of code that are repeated 
in multiple places with little to no variation. 

[X] Install flask_MYsql-
pip3 install flask-mysql