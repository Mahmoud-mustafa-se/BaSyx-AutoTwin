FROM python:3.9-slim

WORKDIR /app

RUN pip install flask requests basyx-python-sdk

COPY . .

# Must match the port mapping in docker-compose.yml
EXPOSE 5000

CMD ["python", "app.py"]
