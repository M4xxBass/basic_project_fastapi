# 🚀 FastAPI Project - Hello World

This is a basic **FastAPI** project that displays a "Hello World" message.


## Create project 
```bash 
uv init fastapi_clean_architecture
```

## Create venv
```bash 
uv venv
.venv\Scripts\Activate.ps1
```

## Add fastapi
```bash
uv add fastapi
```

## Run the project
```bash
uv run uvicorn src.main:app --reload
or
uv run uvicorn src.main:app --port 8000
```

## Unit test
Create a new folder tests , add a new file call test_main.py and the file __init__.py
Create a new folder src , move the main.py file to that directory

### Install packages
```bash
uv add pytest --dev 
uv add pytest-mock --dev
uv add httpx --dev
```

### Coverage
```bash
coverage run -m pytest
coverage report
coverage html
```

## Linter and formatting using Ruff 
```bash
uv add ruff --dev

uvx ruff check src/main.py
uvx ruff check src/main.py --fix
uvx ruff format src/main.py
```

## Testing on postman or ThunderClient
```
localhost:8000/
```