mkdir ./api-project
cd ./api-project
python3 -m venv .venv
source .venv/bin/activate
pip install "fastapi" "uvicorn[standard]"


Users/user/api-project/main.py

from fastapi import FastAPI

app = FastAPI()

@app.get("/")
def read_root():
    return {"Hello": "World"}

     rm /opt/homebrew/bin/pip
 python3 --version\n
 python3 -m ensurepip --upgrade
 python3 -m pip install --upgrade pip
 python3 -m pip install "fastapi" "uvicorn[standard]"

  uvicorn main:app --reload\n
  user@Zhadyra-2 ~ % curl http://127.0.0.1:8000/
{"Hello":"World"}%  

<img width="687" alt="image" src="https://github.com/user-attachments/assets/c1731980-df78-4bb9-b102-977f6d268a4a">
