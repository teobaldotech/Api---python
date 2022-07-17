# Api---python      


from fastapi import FastAPI        

app = FastAPI()

@app.get("/")
def hello_root():
    return {"message": "Hello ,api python"}     # uvicorn main:app --reload
