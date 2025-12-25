on backend. 

pip install fastapi uvicorn pydantic
pip install mappyfile
source venv/bin/activate
uvicorn app.main:app --reload --port 8000