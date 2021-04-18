# weather-app-flask

## Como rodar o projeto?

* Clone esse repositório.
* Crie um virtualenv com Python 3.
* Ative o virtualenv.
* Instale as dependências.
* Rode o App.

```
git clone https://github.com/leandro-matos/weather-app-flask.git
cd weather-app-flask
python3 -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
flask run
```

```
docker run --name weather -d -p 5000:5000 leandromatpereira/weather-app-flask:latest
```

Deploy no Heroku: https://app-weather-flask.herokuapp.com/
