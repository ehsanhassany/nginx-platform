FROM PYTHON:3.8-SLIM

workdir /app

copy requirements.txt .
RUN pip install -r requirements.txt

COPY ..

CMD ["python, "app.py"]
