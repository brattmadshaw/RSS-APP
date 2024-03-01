// Use python 3.8-slim
FROM python:3.8-slim

// set /app as working directory

// copy everything into /app 
COPY . . 

// Install requirements
RUN pip install requirements.txt

// Expose correct port:
EXPOSE 5000 

// use CMD or ENTRYPOINT to start the app:
ENTRYPOINT ["python", "app.py"]
