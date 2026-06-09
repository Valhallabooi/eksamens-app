# eksamens-app

En enkel Flask-app med en startside.

## Kjør lokalt

```bash
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

Åpne deretter `http://127.0.0.1:5000` i nettleseren.

## Kjør med Docker

```bash
docker compose -f compose.yml up --build
```

Åpne deretter `http://127.0.0.1:5000` i nettleseren.
