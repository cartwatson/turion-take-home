FROM python:3.8-slim-buster

WORKDIR /app

RUN apt-get update && apt-get install

COPY . .

RUN pip install -r requirements.txt

CMD ["python", "-u", "mcs.py"]
