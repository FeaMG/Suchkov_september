# FastAPI + SQLite CRUD

Минимальный пример CRUD API на FastAPI + SQLite.

## Установка и запуск

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt

uvicorn app.main:app --reload
```

После запуска API доступно по адресу:
👉 http://127.0.0.1:8000

Документация Swagger UI:
👉 http://127.0.0.1:8000/docs
