# app_python

## intialization
```bash
apt-get install python3-pip
apt-get install python3-venv
python -m venv venv
source venv/bin/activate
pip install flask
```

## Development withou gunicorn
```bash
python3 main.py
pip freeze > requirments.txt

```

## Develoment with guncicorn
```bash
pip install gunicorn 
pip freeze > requirments.txt
gunicorn wsgi
```

# edit from github gui

## from main branch