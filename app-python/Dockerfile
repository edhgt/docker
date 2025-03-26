FROM python:alpine

WORKDIR /app

COPY script.py .
COPY requirements.txt .

RUN pip install -r requirements.txt

CMD ["python", "script.py"]
