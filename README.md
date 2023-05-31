# learn_fashAPI
Download Python(v3.9.6)
Dowload VSCode
Set up virtual enviroment
    Open terminal (CMD)
    Create venv: $py -3 -m venv fastAPI
    Active venv: $fastAPI\Scripts\activate.bat
    Deactive venv: $deactive
Install FastAPI: $pip install fastapi
Install ASGI server (Uvicorn or Hypercorn): $pip install "uvicorn[standard]"
Create main.py #Detail: https://fastapi.tiangolo.com/lo/
Run: $uvicorn main:app --reload //$uvicorn app.main:app --reload  // uvicorn --host 192.168.1.2  app.main:app --reload
Docs: http://127.0.0.1:8000/docs
Redoc:  http://127.0.0.1:8000/redoc
#Create simple CRUD app without DB
why need schema.png
crud.png
error up to down flow 1.png
error up to down flow 2.png
import Response, status from fastapi to handle status code
#Install PostgreSQL
install postgresql.png
install postgresq2.png
    SQL: almost same SQL Server
    select * from products limit 5 offset 2;
    insert into products(name, price, inventory) values ('Smart Watch', 6, 10) returning *
#Install Psycopg - PostgreSQL database adapter for python


