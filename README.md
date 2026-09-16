# copilot-agent-test

## Run the application

```bash
python -m pip install -r requirements.txt
uvicorn app.main:app --reload
```

Then open `http://127.0.0.1:8000/hello`.

## Run tests

```bash
pytest
```