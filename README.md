### ________________________________________
# Criando uma calculadora de gasto de caloria basal

Um projeto simple em Python usando framework flask e postgreSQL.


### ________________________________________
### Crie um arquivo config.py
import os

class Config:
    SECRET_KEY = ''
    SQLALCHEMY_DATABASE_URI = 'postgresql://usuario:senha@localhost:5432/calculationbasal'
    SQLALCHEMY_TRACK_MODIFICATIONS = False





### ________________________________________
### PostgreSQL criar DB

 > CREATE DATABASE calculationbasal;
#
### ________________________________________
## Terminal do Pycharm
### ________________________________________
## Install
 > pip install -r requirements.txt

## Caso precise fazer Migração
 > pip install Flask-Migrate
 >> flask db init
 >>> flask db migrate -m "Migração inicial"
 >>>> flask db upgrade


## Run
 > flask run
