## How to start dev mode?
1. Create `.env` file and paste the following: 
```
SETTINGS_SECRET_KEY=secret1
CATALOG_SECRET_KEY=secret2
HOMEPAGE_SECRET_KEY=secret3
```
1. Create your **venv** by terminal command: `python3 -m venv {venvname}`
1. Activate the **venv**: `source {venvname}/bin/activate`
1. Install dev dependencies: `pip3 install -r requirements/dev.txt`
1. Go to directory of needed project: `cd about` / `cd catalog` / `cd homepage`
1. Launch a server: `python3 manage.py runserver`
