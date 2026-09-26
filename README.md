# Studio Cart

An intentionally minimal Django ecommerce demo that is currently under construction. The homepage communicates the project status; the original catalogue models remain available as the next build stage.

## Requirements

- Python 3.13
- Django 6.1.1

## Run locally

```powershell
py -3.13 -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Open http://127.0.0.1:8000/.

This is a development demo. Set a new `SECRET_KEY`, turn off `DEBUG`, and configure allowed hosts before deployment.
