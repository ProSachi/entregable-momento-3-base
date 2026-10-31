Activar ambiente virtual
source venv/Scripts/activate

Instalar dependenciar
pip install -r requirements.txt

Levantar microservicio
uvicorn microservicio:app --reload --port 8000

