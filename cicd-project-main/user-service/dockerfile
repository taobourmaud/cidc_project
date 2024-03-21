FROM python:3.9-alpine3.13

WORKDIR /app

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . .

EXPOSE 3001

CMD ["flask", "run", "--host=0.0.0.0", "--port=3001"]