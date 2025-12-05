# Installation instructions

- create virtual env `exp-tracking-env` (skip if already present): `uv venv exp-tracking-env`
- activate the virtual env: `source exp-tracking-env/bin/activate`
- install requirements: `uv pip install -r requirements.txt`
- run mlflow by leveraging a local sqlite database: `mlflow ui --backend-store-uri sqlite:///mlflow.db`
- navigate to `http://127.0.0.1:5000/` to open the ui

