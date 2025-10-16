## Comando para que python este actualizado, solo aplicable en los computadores de la sede

```bash
c:\ProgramData\anaconda3\Scripts\activate.bat

````
python -m venv venv
```

```bash
venv\Scripts\activate

```

creamos un archivo `requirements.txt`para las dependencias de la aplicacion


```txt
Django
python-dotenv
gunicorn
psycopg2
```

Django: Framework a utilizar
Python .env: Leer variables de entorno
gunicorn: Utilizar para WSGI
psycopg2:Conector con PostgreSQL



Una vez activado el ambiente debemos de instalar las dependencias

```bash
pip install -r requirements.txt
```


```bash
django-admin starproject main
```


```bash
django-admin starapp venta
```





```

