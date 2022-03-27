1.stworzyć folder
mkdir FlaskApp
cd FlaskApp

2.utworzyć środowisko wirtualne
py -3 -m venv venv

3.aktywować je
venv\Scripts\activate

4.zainstalować flaska
pip install Flask

5.stworzyć plik app.py z zawartością:

from flask import Flask

app = Flask(__name__)


@app.route('/')
def hello():
    return '<p>Hello World<p>'


if __name__ == '__main__':
    app.run()
6. zapisanie pliku do folderu FlaskApp
7.deklaracja flaskapp
set FLASK_APP=app.py
8.odpalić
 flask run
9.skopiować adres url i wkleić do wyszukiwarki
  
