RUN `uvicorn main:app --reload` # Run the server

Frontend app served as static at localhost:8000

calling /api will proxy to localhost:8000/api during development and will call the same domain in production
