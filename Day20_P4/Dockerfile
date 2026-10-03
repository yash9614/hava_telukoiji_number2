FROM python:3.12-slim

WORKDIR /app

COPY Day20/requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

COPY Day20 /app/Day20

WORKDIR /app/Day20

EXPOSE 8000

CMD ["uvicorn","main:app",  "--host","0.0.0.0","--port",  "8000"]
