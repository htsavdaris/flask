# flask
Flask Play 

python3 -m venv venv
.\venv\Scripts\activate
pip install Flask
pip install waitress

 waitress-serve --url-prefix=/my-app --listen=127.0.0.1:8001 main:app
