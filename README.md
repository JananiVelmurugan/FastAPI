# FastAPI
This repository consists of FastAPI code with all four types of HTTP Methods - Post, Get, PUT, Delete

# Steps
1. PS D:\2026\GitProjects\FastAPI> python -m venv venv
2. PS D:\2026\GitProjects\FastAPI> venv\Scripts\Activate.ps1(windows) or source venv/bin/activate(mac)
3. (venv) PS D:\2026\GitProjects\FastAPI> pip install -r requirements.txt
4. (venv) PS D:\2026\GitProjects\FastAPI> uvicorn main:app --reload (default port is 8000)
5. (venv) PS D:\2026\GitProjects\FastAPI> uvicorn main:app --reload --port 8080 (to change the port)
6. To test the home page api, navigate to http://127.0.0.1:8000/ in the browser
7. To access the swagger docs of the app, navigate to http://127.0.0.1:8000/docs in the browser

# Notes
* uvicorn is the server where the FastAPI runs
* To access docs of FastAPI, type FastAPI pypi

