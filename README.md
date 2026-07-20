# alex-job-hunter-ai
Sua Ia que traz o emprego certo 
alex-job-hunter-ai/

backend/
frontend/
docs/
docker/
database/
backend/

app/
 ├── main.py
 ├── routes/
 ├── models/
 ├── services/
 ├── database/
 └── ai/
 from fastapi import FastAPI

app = FastAPI(
    title="Alex Job Hunter AI",
    version="1.0.0"
)

@app.get("/")
def home():
    return {
        "project": "Alex Job Hunter AI",
        "status": "online"
    }
