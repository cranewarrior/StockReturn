install python 3.7

upgrade pip

py -m pip install --upgrade pip

create virtualenv

py -m virtualenv env

.\env\Scripts\activate

pip3 install -r requirements.txt

pip3 freeze > requirements.txt

env FLASK_DEBUG=1 python -m flask run --port 5000