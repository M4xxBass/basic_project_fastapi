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
uv run uvicorn main:app --reload
or
uv run uvicorn main:app --port 8000
```

## Testing on postman or ThunderClient
```
localhost:8000/
```