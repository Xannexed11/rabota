FROM python:alpine

WORKDIR /app

COPY main.py . package.json .

RUN npm install

ENTRYPOINT ["python", "main.py"]
