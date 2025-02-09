### Fastapi

* FastAPI is a modern, fast (high-performance), web framework for building APIs with Python based on standard Python type hints.
* Uvicorn is an ASGI server (Asynchronous Server Gateway Interface) used to run Python web applications that are built using ASGI-compatible frameworks like FastAPI or Starlette.
* In simple terms, Uvicorn is the tool that runs your web application (such as FastAPI) by acting as the server to handle incoming HTTP requests, route them to your application code, and send back responses.
* Refer - https://fastapi.tiangolo.com & https://fastapi.tiangolo.com/tutorial/
  - Install using 
    ```bash
      pip install "fastapi[standard]"
    ```
  - Run the fast api in some different port:
    ```bash
      cd fast_api
      uvicorn main:app --reload --port 8001
    ```  
  - Running the live server via:
    ```bash
      fastapi dev fast_api/main.py
    ```
  - CTRL-C and you can stop the server.