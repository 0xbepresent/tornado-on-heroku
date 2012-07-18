tornado-on-heroku
=================

Implementacion de Tornado dentro de Heroku. 

Para correr la aplicacion.

$ git clone https://github.com/misalabs/tornado-on-heroku.git
$ cd tornado-on-heroku
$ python app/main.py

Abrir el navegador en 
http://127.0.0.1:5000


Para subir estos archivos a heroku

$ heroku create --stack cedar
$ git push heroku master

