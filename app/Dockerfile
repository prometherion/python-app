FROM python:3.11.0b3-alpine3.16

WORKDIR /workspace
COPY . .
RUN pip install -r requirements.txt
EXPOSE 8080
ENV MSG default
ENTRYPOINT ["python", "server.py"]
