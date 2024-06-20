# Enquetes

## Sobre
Este projeto é semelhante ao realizado no tutorial da [documentação oficial](https://docs.djangoproject.com/pt-br/5.0/intro/tutorial01/) do django.

## Pré-requisitos
Instale as bibliotecas necessárias com ```pip install -r requirements.txt```.

## Banco de Dados
Neste projeto foi utilizado o banco de dados [PostgreSQL](https://www.postgresql.org/download/). E utilizado a lib [django-environ](https://django-environ.readthedocs.io/en/latest/install.html).

Para utilizá-la crie um arquivo ```.env``` com 
```
DEBUG=on
DATABASE_URL=psql://user:password@127.0.0.1:5432/databasename
```

E inclua no seu arquivo [settings](enquetes/mysite/mysite/settings.py) as configurações como consta neste projeto.