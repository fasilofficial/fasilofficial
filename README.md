<h1 align='center'>Hey <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f44b/512.gif" alt="👋" width="32" height="32">, I'm Fasil </h1>
<h4 align="center">DEVELOPER. PHOTOGRAPHER. CINEPHILE.</h4>

```python



from fastapi import FastAPI
from fastapi.responses import JSONResponse

app = FastAPI()

@app.get("/about")
async def about():
    return JSONResponse(content={
        "fullName": "Muhammed Fasil K",
        "interests": ["coding", "movies", "music", "travel"],
        "skills": ["ReactJS", "Node.js", "Laravel", "Python", "SQL", "NoSQL", "FasilAPI"]
    })

@app.get("/contact")
async def contact():
    return JSONResponse(content={
        "email": "muhammedfasilofficial@gmail.com",
        "portfolio": "https://mfasil.vercel.app"
    })

@app.exception_handler(404)
async def not_found(request, exc):
    return JSONResponse(content={"message": "Route not found"}, status_code=404)

```
